### In order to run this notebook you need Python3 and Git installed locally

### SET UP A VIRTUAL ENVIRONMENT ###

#### Install virtual environment
```$ pip3 install virtualenv``` 

#### Set up a virtual environment with python in the Tensorflow-Workshop directory 
```$ python3 -m virtualenv TF-WorkshopVE```


#### Activate virtual environment
##### Mac and Linux
```$ source TF-WorkshopVE/bin/activate```

##### Windows
```.\TF-WorkshopVE\Scripts\activate```

#### Update pip

##### Mac and Linux
```$ pip3 install --upgrade pip```

##### Windows 
```python3 -m pip install --upgrade pip```

#### Install dependencies
```$ pip3 install -r requirements.txt```

#### Add virtual environment as jupyter kernel
```$ ipython kernel install --user --name=TF-Workshop```

#### Open jupyter in browser
```$ jupyter notebook```
