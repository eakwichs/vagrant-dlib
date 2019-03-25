# vagrant-dlib
- Virtual machine in VirtualBox running Ubuntu 18.04

## Set Up
**Creates and configures guest machines**
- `vagrant up`

**Option, Forces reprovisioning of the vagrant machine**
- `vagrant provision`

**Connects to vagrant machine via SSH**
- `vagrant ssh`

**Option, Terminate the virtual machine**
- `vagrant destroy`

**Check python version**
- `python -V`
    > Python 2.7.15rc1
    
- `python3 -V`
    > Python 3.6.7
    
**Check pip version**
- `pip2 --version`
    > pip 19.0.3 from /usr/local/lib/python2.7/dist-packages/pip (python 2.7)

- `pip3 --version`
    > pip 19.0.3 from /usr/local/lib/python3.6/dist-packages/pip (python 3.6)
    
**Create a virtual environment**
- `mkvirtualenv venv -p python3`
    > (venv) vagrant@ubuntu-bionic:~$
    
**Option, If you needs to activate this virtual environment next time, do this**
- `workon venv`

**Option, If you needs to deactivate this virtual environment, do this**
- `deactivate`

**Check python version in this virtual environment**
- `python -V`
    > Python 3.6.7

**Check pip version in this virtual environment**
- `pip --version`
    > pip 19.0.3 from /home/vagrant/.virtualenvs/venv/lib/python3.6/site-packages/pip (python 3.6)
    
**Install NumPy**
- `pip install numpy`
 
**Install Dlib**
- `pip install dlib`
