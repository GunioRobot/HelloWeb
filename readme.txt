���run.bat����web.py������server

ngnix

url.rewrite-once = (
��^/favicon.ico$�� => ��/static/favicon.ico��,
��^/static/(.*)$�� => ��/static/$1��,
��^/(.*)$�� => ��/code.py/$1��,
)

