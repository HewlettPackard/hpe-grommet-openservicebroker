# osb-grommet-python
Simple Python script to get a Broker running grommet application

Pre-requisites:
  - python2/python3 ( sudo apt-get install python or from other sources as per distro)
  - pip/pip3 (Can refer to https://pip.pypa.io/en/stable/installing/  or sudo apt-get install python-pip or other sources)

Change `host` <ip> to the `machine ip` in file osb_template.py , set `PORT` environment variable for port
> bottle.run(host='172.18.203.43', port=port, debug=True, reloader=False, server='gunicorn')
Note: if using public VM, port should be opened for access.

Python2:
- sudo pip install --no-cache-dir -r requirements.txt
- python osb_template.py

OR 

Python 3:
- sudo pip3 install --no-cache-dir -r requirements.txt
- python3 osb_template.py

Note: this guide only covers the basic steps for starting the broker in minimum steps, based on the requirements the usage can be extended.
