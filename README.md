# mod_jk_and_apr_builds
compiled builds for centos 7

APR:

Versions:
a) APR v1.5.2
b) APR-util 1.5.4
c) Tomcat Native Library 1.2.5 

Procedure:

a) Unzip this archive to /usr/local directory

b) Add below enviornment variable

    export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/usr/local/apr/lib
c) Start Tomcat Server

Mod_JK:

Procedure:

a) Copy mod_jk.so file  to /usr/lib64/httpd/ folder
b) Assign Correct Permissions
