# Sample Application with Python and Flask

This sample is running on: https://python2-flask.is-easy-on-scalingo.com/

## Run Locally

```shell
virtualenv
. bin/activate
pip install -r requirements.txt
python app.py
```

## Deploy via Git

Create an application on https://scalingo.com, then:

```shell
git remote add scalingo git@ssh.osc-fr1.scalingo.com:<name_of_your_app>.git
git push scalingo master
```

And that's it!

The application is running at this URL: https://<name_of_your_app>.osc-fr1.scalingo.io/

## Deploy via one-click

[![Deploy to Scalingo](https://cdn.scalingo.com/deploy/button.svg)](https://my.scalingo.com/deploy)
