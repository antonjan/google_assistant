# google_assistant
This repository will have my Google Assistant development code.
I am trying to create a voise operated banking app to do payments and get statemets.<br>


<b>Installation.</b><br>
<b>Audio check</b><br>
speaker-test -t wav<br>
arecord --format=S16_LE --duration=5 --rate=16000 --file-type=raw out.raw<br>
play --format=S16_LE --rate=16000 out.raw<br>
<br>
sudo apt-get update<br>
sudo apt-get install python3-dev python3-venv<br>
 1614  python3 -m venv env<br>
sudo apt-get install python-dev python-virtualenv<br>
python -m pip install --upgrade google-assistant-library<br>
python -m pip install --upgrade google-auth-oauthlib[tool]<br>

google-oauthlib-tool --client-secrets client_secret_????.com.json  --scope https://www.googleapis.com/auth/assistant-sdk-prototype --save --headless<br>

git clone https://github.com/googlesamples/assistant-sdk-python<br>
cp -r assistant-sdk-python/google-assistant-sdk/googlesamples/assistant/library anton_google_project<br>
<br>
sudo python -m pip install --upgrade google-assistant-library<br>
<br>
<b>Testing your Google Assistand after instelation.</b><br>
google-assistant-demo<br>
