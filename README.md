![flake8](https://github.com/danielmellado/openshift-versions/workflows/flake8/badge.svg?branch=master)

# openshift-versions

Run the python script to generate an html page with the list of the latest OpenShift 4 versions.

See it live at [versions.openshift.tips](http://versions.openshift.tips)

## Install

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run

```bash
source .venv/bin/activate
python versions.py
```

Then, copy the html somewhere to be served by any web server.
