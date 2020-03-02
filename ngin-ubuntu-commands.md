##  commands 
---
*sudo  apt-get update*
*sudo  apt-get install software-properties-common*
*sudo  add-apt-repository universe*
* sudo  add-apt-repository ppa:a certbot/certbot
*sudo  apt-get update*
*sudo  apt-get install python-certbot-nginx*
* here is where you might want to chanage the SERVERNAME (if set to IP) to Domain Name
*sudo  certbot --nginx*
*sudo  certbot renew --dry-run*