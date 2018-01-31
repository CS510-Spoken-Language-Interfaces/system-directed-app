# Getting Started

Please follow the instructions in the pre-requisites before deploying the project on your local machine.

## Pre-requisites

1. Install Google Cloud SDK
2. Create a project in google cloud console
3. Enable Google Cloud Speech API by adding it from library under APIs and Services.
4. Create a service account
5. Download the service account key file (.json) to the folder where you are going to deploy/run the project.
6. Create an environment variable GOOGLE_APPLICATION_CREDENTIALS as `GOOGLE_APPLICATION_CREDENTIALS=/path/to/service_account.json
=/path/to/service_account.json`

```
Note: All the above instructions can be found on Google Cloud Speech Quickstart Guide (https://cloud.google.com/speech/docs/quickstart) 
```
7. Install [Python](https://www.python.org/downloads/)
8. Install Pip. Follow this [guide](https://github.com/BurntSushi/nfldb/wiki/Python-&-pip-Windows-installation)
9. Install [PyAudio](https://people.csail.mit.edu/hubert/pyaudio/)
10. Install [PyTTSx3](https://github.com/nateshmbhat/pyttsx3/blob/master/README.rst)

```
Note: As of when this article was written, I got error while running the sample program , I was able to solve the same
using link (https://github.com/nateshmbhat/pyttsx3/issues/1)
```

## 


