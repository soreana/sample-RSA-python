# Config dependencies.
### Step one: install pip3 [[1]](https://www.liquidweb.com/kb/how-to-install-pip-on-ubuntu-16-04-lts/)
* Execute `curl "https://bootstrap.pypa.io/get-pip.py" -o "get-pip.py"` to get pip installation script.
* Execute `sudo -H python3 get-pip.py` to install pip3 (cryptography needs python3 as a result we should install pip3)

### Step two: install some dependencies:
* Run `sudo apt-get install python3.6-dev libmysqlclient-dev`

### Step tree: cryptography installation
* Install cryptography library for current user by `pip3 install cryptography --user`


## How to run each file
