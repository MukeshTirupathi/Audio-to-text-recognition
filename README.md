# realtime-transcription

# 1. Obtain the AssemblyAI API key

Obtain your free [AssemblyAI API key](https://app.assemblyai.com/).

# 2. Running the Audio to text recognition web app
To recreate this web app on your own computer, do the following.

### Create conda environment (Optional)
Firstly, we will create a conda environment called *transcription*
```bash
conda create -n transcription python=3.7.9
```
Secondly, we will login to the *transcription* environment
```bash
conda activate transcription
```

###  Download GitHub repo

```bash
git clone https://github.com/MukeshTirupathi/Audio-to-text-recognition.git
```

###  Pip install libraries
```bash
pip install websockets
pip install asyncio
pip install 
pip install pyaudio

```

###  Launch the app

```bash
streamlit run streamlit_app.py
```
