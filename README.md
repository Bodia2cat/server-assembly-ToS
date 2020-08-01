# server-assembly-ToS
## assembly for ToS srver


#             How to use

1) apt install apache2 openssh-srver phpmyadmin mysql
2) Copy apache2.conf and sshd_config to /etc/apache2/ and /etc/ssh/
3) Copy tos.zip to /home/%user%/
4) Copy ssh.sh to /home/%user%/
5) install noip
6) noip2 -C
7) Copy apache2.zip to /var/www/html/
8) sudo service apache2 restart
9) sudo service sshd restart
