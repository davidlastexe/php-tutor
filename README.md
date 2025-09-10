# php-tutor

### Install xampp
```bash
sudo apt update -y && sudo apt upgrade -y
wget https://sourceforge.net/projects/xampp/files/XAMPP%20Linux/8.2.12/xampp-linux-x64-8.2.12-0-installer.run
chmod +x xampp-linux-x64-8.2.12-0-installer.run
sudo ./xampp-linux-x64-8.2.12-0-installer.run
```

```bash
sudo ln -s /opt/lampp/bin/php /usr/local/bin/php
sudo ln -s /opt/lampp/xampp /usr/local/bin/xampp
sudo chmod -R 777 /opt/lampp/htdocs
sudo chmod -R 777 /opt/lampp/mysql
sudo chmod 755 /opt/lampp/var/mysql
```

### In order to start all the xampp services, we need to run the following command in the terminal:
```bash
sudo /opt/lampp/xampp start
sudo /opt/lampp/xampp stop
sudo /opt/lampp/xampp restart
```
or
```bash
sudo xampp start
sudo xampp stop
sudo xampp restart
```

### Xampp help
```bash
sudo /opt/lampp/xampp --help
```

### Xampp uninstall
```bash
sudo /opt/lampp/uninstall
```
