# A Tour of Python

## Install requirements
```
$ pip install -r requirements.txt
```

## Install RISE Jupyter extension
```
$ jupyter-nbextension install rise --py --sys-prefix
```

## Enable the nbextension
```
$ jupyter-nbextension enable rise --py --sys-prefix
```

## Set up Tweepy
Put credentials in a Jupyter startup script, e.g. in ~/.ipython/profile_default/startup/00-first.py:
```
CONSUMER_API_KEY = YOUR_CONSUMER_API_KEY
API_SECRET_KEY = YOUR_API_SECRET_KEY
ACCESS_TOKEN = YOUR_ACCESS_TOKEN
ACCESS_TOKEN_SECRET = YOUR_ACCESS_TOKEN_SECRET 
```

## Run it
```
$ jupyter notebook demo.ipynb
```

## Generate static slides
```
jupyter nbconvert --to slides demo.ipynb
```
