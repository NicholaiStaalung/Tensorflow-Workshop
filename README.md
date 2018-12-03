### SET UP A VIRTUAL ENVIRONMENT ###

#### Install virtual environment in the Tensorflow-Workshop folder
```$ pip3 install virtualenv``` 

#### Set up a virtual environment with python 
```$ python3 -m virtualenv TF-WorkshopVE```


#### Activate virtual environment
##### Mac and Linux
```$ source TF-WorkshopVE/bin/activate```

##### Windows
```.\TF-WorkshopVE\Scripts\activate```

#### Update pip
```$ pip3 install --upgrade pip```

#### Install dependencies
```$ pip3 install -r requirements.txt```

#### Add virtual environment as jupyter kernel
```$ ipython kernel install --user --name=TF-Workshop```

#### Open jupyter in browser
```$ jupyter notebook```
