# Editorial

Scanning & Recon
-------

Performing a intensive nmap scan on the ip address I get:

ports open:
* 22 - ssh - OpenSSH 8.9p1 Ubntu
* 80 - http - nginx 1.18.0 -> did not redirect to "http://editorial.htb"

Trying to access the website it does not work. -> changing the etc/hosts to gain acces

Website components:
- upload page
  -  allows files to be uploaded
    - updates a image on that page
    - it stores it in "/static/images/...." and then displays


Exploitation
-----------

Possible Explotation found:
- upload a PHP file and run it??

post-Exploitation
-----------
