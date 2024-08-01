FROM python:3.12

RUN python3 -m pip install --upgrade pip

RUN python3 -m pip install https://github.com/alphacep/vosk-api/releases/download/v0.3.42/vosk-0.3.42-py3-none-linux_x86_64.whl

RUN apt update -y && apt install -y libasound-dev portaudio19-dev libportaudio2 libportaudiocpp0 ffmpeg

RUN python3 -m pip install pyaudio

# RUN apk add py3-pyaudio 
