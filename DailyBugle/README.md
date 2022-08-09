## NMAP

nmap -sV -O -T4 -Pn 10.10.33.225 -oN nmap/initial

22/tcp   open  ssh     OpenSSH 7.4 (protocol 2.0)
80/tcp   open  http    Apache httpd 2.4.6 ((CentOS) PHP/5.6.40)
3306/tcp open  mysql   MariaDB (unauthorized)

## Gobuster scan

Nothing fiund

## Curl

Apache 2.4.6
PHP 5.6.40