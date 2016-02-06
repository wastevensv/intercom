# Intercom
CSH Intercom Project.

## Install dependencies
```
# Python 2.7
sudo apt-get install python-pip espeak python-dev
pip install -r requiremnets.txt

# Python 3.4
sudo apt-get install python3-pip espeak python3-dev
pip3 install -r requirements.txt

or

./setup.sh
```

## Start the server
```
python server/server.py

or (requires rkt)

sudo ./build-server-intercom.sh
sudo rkt run --insecure-options=image wasv.me/intercom
```

## Send a message
```
echo [your server ip] >> server.key.txt
python client/client.py
```

## Future plans
* Absolute times instead of delays.
* Web Interface

## Client setup Installation
```
sudo apt-get install python-pip espeak python-dev
pip install -r requirements.txt
python client/client.py


or


./setup.sh
```
