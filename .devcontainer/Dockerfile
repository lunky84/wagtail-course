FROM mcr.microsoft.com/devcontainers/python:0-3.11

COPY requirements.txt ./

RUN pip install --no-cache-dir --upgrade pip \
    && pip install --no-cache-dir -r requirements.txt

ENV HISTFILE=/home/vscode/.bash_history
COPY .bash_history /home/vscode/