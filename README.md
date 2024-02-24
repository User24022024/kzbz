﻿# Lyrid Python 3.10 Flask Template

## Set virtual environment(optional):
```
python -m venv venv
source venv/bin/activate
```

## Run locally with:
```
pip install -r requirements.txt
python main.py
```

Open http://localhost:3000

## Edit the names (optional):
Open .lyrid-definition and change the App and Module name, because this will override another applications with the same name in the platform.

## Then submit to Lyrid Platform:

```
lc code submit
```
Wait until the cloud platform to finish with the build and the default deployment.

## Start hacking:

Edit the routes at /entry/entry.py with your custom API. 

Add more middlewares or your business logic in there.
