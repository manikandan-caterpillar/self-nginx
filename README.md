
# Windows
start nginx -p /Users/arumum11/nginx

nginx -s stop -p /Users/arumum11/nginx

openssl version

nginx -v
nginx -h

C:\Program Files\Git\usr\bin\openssl.exe

Confis in -> c:\nginx-1.17.0\conf\
Default config -> c:\ nginx-1.17.0\conf\nginx.conf
Logs will be in -> c:\ nginx-1.17.0\logs
Default webroot is -> c:\ nginx-1.17.0\html\
Default listen address -> http://localhost

nginx -s stop	fast shutdown
nginx -s quit	graceful shutdown
nginx -s reload	changing configuration, starting new worker processes with a new configuration, graceful shutdown of old worker processes
nginx -s reopen	reopening log files


