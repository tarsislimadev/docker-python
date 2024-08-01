FROM python:alpine

RUN python3 -m pip install --upgrade pip

RUN python -m pip install https://github.com/alphacep/vosk-api/releases/download/v0.3.42/vosk-0.3.42-py3-none-linux_x86_64.whl

# RUN python -m pip install pyaudio

RUN apk add py3-pyaudio 
