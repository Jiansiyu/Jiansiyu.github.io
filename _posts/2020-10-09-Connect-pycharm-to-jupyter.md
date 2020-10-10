---
title: 'Connect Jupyter Notebook to Pycharm-professional'
date: 2020-10-10
permalink: /posts/2020/10/pychamconfigure/
tags:
  - Linux
  - pycharm
  - Jupyter
---

Connect the Pycharm-professional to the Jupyter Notebook

---
## Connect to Pycharm manually

#### Step.1 Create Virtual Eviroment

```
python3 -m venv venv
```

#### Step.2 Load the virtual Eviroment
```
source venv/bin/active
```

#### step.3 install the package 
```
pip install jupyter
```

#### step.3 Connect pycharm to Jupyter Server 
Set the Jupyter Server to `http://localhost:8888`
