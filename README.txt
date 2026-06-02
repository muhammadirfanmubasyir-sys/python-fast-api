VENV
====
D:\PROJECTS\python\simple-fastapi-example>python -m venv .venv

D:\PROJECTS\python\simple-fastapi-example>.venv\Scripts\activate

(.venv) D:\PROJECTS\python\simple-fastapi-example>pip install -r requirements.txt

RUN
===
$ uvicorn main:app --reload
INFO:     Will watch for changes in these directories: ['/mnt/d/PROJECTS/python/simple-fastapi-example']
INFO:     Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)
INFO:     Started reloader process [61247] using StatReload
INFO:     Started server process [61249]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
INFO:     127.0.0.1:50906 - "POST /items HTTP/1.1" 200 OK
INFO:     127.0.0.1:34976 - "POST /items HTTP/1.1" 200 OK
INFO:     127.0.0.1:41640 - "GET /items HTTP/1.1" 200 OK
INFO:     127.0.0.1:58882 - "GET /items?limit=1 HTTP/1.1" 200 OK
INFO:     127.0.0.1:46002 - "POST /items HTTP/1.1" 200 OK
INFO:     127.0.0.1:46004 - "GET /items?limit=2 HTTP/1.1" 200 OK
INFO:     127.0.0.1:59046 - "GET /items/2 HTTP/1.1" 200 OK
INFO:     127.0.0.1:33174 - "GET /items/3 HTTP/1.1" 404 Not Found
INFO:     127.0.0.1:58628 - "GET /items/1 HTTP/1.1" 200 OK
INFO:     127.0.0.1:58642 - "GET /items/0 HTTP/1.1" 200 OK
WARNING:  StatReload detected changes in 'main.py'. Reloading...
INFO:     Shutting down
INFO:     Waiting for application shutdown.
INFO:     Application shutdown complete.
INFO:     Finished server process [61249]
INFO:     Started server process [61317]
INFO:     Waiting for application startup.
INFO:     Application startup complete.