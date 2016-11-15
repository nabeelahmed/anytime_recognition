# Anytime Visual Recognition

The repo is forked from [sergeyk/anytime_recognition](https://github.com/sergeyk/anytime_recognition)

The project page - with [publications](http://sergeykarayev.com/recognition-on-a-budget)

## To get started

**Install the os (CentOS 7) level dependencies**

`sudo yum install python-devel python-pip`
```
sudo yum install atlas-devel lapack-devel blas-devel libgfortran
sudo yum -y install hdf5-devel
sudo yum -y install tkinter
```

(Optional) **Create a virtualenv**: the new python packages will be installed in this new venv - more about [virtualenv here](http://devopspy.com/python/what-is-virtualvenv/).
```
pip install virtualenv
virtualenv venv_anytime_rc
source venv_anytime_rc/bin/activate
```

**Clone the project repo**:
`git clone https://github.com/nabeelahmed/anytime_recognition.git`


**Python packages** cd into project dir i.e. anytime_recognition/ simply run the following command while in project root:

`pip install -r requirements.txt`

---
## Probable issues

> OSError: [Errno 2] No such file or directory: '/home/your-username/anytime_recognition/281b/digits'

Create 281b/ directory at your project root:

`mkdir 281b`
