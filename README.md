###Description

This is a streamlit application using Facebook Audicraft Musicgen model. We have used ```musicgen-small``` model here for inference. You can yield better results by changing the model to ```musicgen-melody``` or ```musicgen-large``` .

###How to use

1. Clone the repository ```music-and-video-gan``` using git
``` git clone https://github.com/Jiya126/music-and-video-gan.git```
2. Go inside the cloned repository
``` cd music-and-video-gan```
3. Install the dependicies and packages required
``` pip install -r requirements.txt```
  It is suggested to create a conda environment. Following are the steos to make a conda environment
  ```
  conda create -n mvgan
  conda activate mvgan
  pip install -r requirements.txt
```
4. Go inside audiocraft folder and run teh streamlit application
```
cd audiocraft
streamlit run app.py
```
5. The application will run on a local host, wherein you can provide the text prompt and press ```Ctrl+Enter``` to generate music based on the prompt given.

