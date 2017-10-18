# google_assistant
This repository will have my Google Assistant development code.
I am trying to create a voise operated banking app to do payments and get statemets.


Instelation.
<b>Audio check</b>
speaker-test -t wav
arecord --format=S16_LE --duration=5 --rate=16000 --file-type=raw out.raw
play --format=S16_LE --rate=16000 out.raw

sudo apt-get update
sudo apt-get install python3-dev python3-venv
 1614  python3 -m venv env
sudo apt-get install python-dev python-virtualenv
python -m pip install --upgrade google-assistant-library
python -m pip install --upgrade google-auth-oauthlib[tool]

google-oauthlib-tool --client-secrets client_secret_????.com.json  --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless

git clone https://github.com/googlesamples/assistant-sdk-python
cp -r assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/library anton_google_project

sudo python -m pip install --upgrade google-assistant-library

Testing your Google Assistand after instelation.
google-assistant-demo
