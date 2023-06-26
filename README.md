# Google login with FastAPI

First, copy `.env.sample` to `.env`:

    $ cp .env.sample .env

Create your Google OAuth Client and fill the client ID and secret
into `.env`, install requirements :
    
    $ pip install -r requirements.txt

and run:
    
    $ python main.py

When register your Google OAuth Client, remember to put:

    http://127.0.0.1:8000/auth

into the client redirect uris list.
