
Versions:
a) Cent OS 7
b) APR v1.5.2
c) APR-util 1.5.4
d) Tomcat Native Library 1.2.5 

Procedure:

a) Unzip this archive to /usr/local directory

b) Add below enviornment variable

    export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/usr/local/apr/lib
c) Start Tomcat