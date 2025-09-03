# php-tutor

### Install xampp
```bash
sudo apt update -y && sudo apt upgrade -y
wget https://sourceforge.net/projects/xampp/files/XAMPP%20Linux/8.2.12/xampp-linux-x64-8.2.12-0-installer.run
chmod +x xampp-linux-x64-8.2.12-0-installer.run
sudo ./xampp-linux-x64-8.2.12-0-installer.run
```

```bash
sudo ln -s /opt/lampp/bin/php /usr/bin/php
```

### In order to start all the xampp services, we need to run the following command in the terminal:
```bash
sudo /opt/lampp/xampp start
sudo /opt/lampp/xampp stop
sudo /opt/lampp/xampp restart
```

### Start Apache only:
```bash
sudo /opt/lampp/xampp startapache
sudo /opt/lampp/xampp stopapache
```

### Start Proftpd FTP server only:
```bash
sudo /opt/lampp/xampp startftp
sudo /opt/lampp/xampp stopftp
```

### Start MySQL Database server only:
```bash
sudo /opt/lampp/xampp startmysql
sudo /opt/lampp/xampp stopmysql
```

### Xampp help
```bash
sudo /opt/lampp/xampp --help
```

### Xampp uninstall
```bash
sudo /opt/lampp/uninstall
```

### Full create, edit,...
```bash
sudo chmod -R 777 /opt/lampp/htdocs
```
