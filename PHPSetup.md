# PHP Installation 

### Update package index
```
$ sudo apt-get update
```

### Install Apache2 server
```
$ sudo apt-get install apache2
```

### Apache configuration file
```
$ sudo vim /etc/apache2/apache2.conf
```

Update domain or public IP in configuration file 
```
ServerName server_domain_or_IP
```

### Restart apache server 
```
$ sudo systemctl restart apache2
```

### Reference 
* [PHP Installation](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04)
