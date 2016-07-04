# Requirements

We're suck using python 2.7 because of pytumblr .

## Packages

* pocket
* python-twitter
* pytumblr

# Install
Requires a file called secrets.py which is not included (see below).

# Using the scripts

Find the string 'jonathankoren' in the script and change it to your username. 

Change the value of the PATH variable (if there is one) to the directory where you want to save files.

## secrets.py

This file should contain your API and access tokens. Its format is:

```python
app_keys = {
  'pocket': {
     'consumer_key': '',    # some key
   },
   'tumblr' : {
     'consumer_key': '',    # some key
     'consumer_secret': '', # some key
   },
   'twitter' : {
     'consumer_key': '',    # some key
     'consumer_secret': '', # some key
   },
}

access_keys = {
  'jonathankoren' : {	    # a specific account. You can change this, but
                            # you'd have to modify the code as well.
    'pocket': {
       'access_token': '',  # some key
    },
    'tumblr' : {
      'access_token': '',   # some key
      'access_secret': '',  # some key
    },
    'twitter' : {
      'access_token': '',   # some key
      'access_secret': '',  # some key
    },
  },
}
```
