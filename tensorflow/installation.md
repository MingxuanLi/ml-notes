## Install tensorflow on Mac

https://www.tensorflow.org/install/install_mac

### Installing with Virtualenv

```
pip install --upgrade virtualenv
virtualenv --system-site-packages -p python3 ~/tensorflow
cd ~/tensorflow
source ./bin/activate 

easy_install -U pip
pip3 install --upgrade tensorflow  

// Command to deactivate
deactivate

// Command to activate
cd ~/tensorflow
source ./bin/activate
```
