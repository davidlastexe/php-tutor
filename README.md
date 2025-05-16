# php-tutor

### Install xampp
```bash
sudo -s
apt update
apt upgrade
wget https://linktodownloadxamppxampp-linux-x64-7.1.10-0-installer.run
chmod +x xampp-linux-x64-7.1.10-0-installer.run
./xampp-linux-x64-7.1.10-0-installer.run
```

```bash
sudo ln -s /opt/lampp/bin/php /usr/bin/php
```

### In order to start all the xampp services, we need to run the following command in the terminal:
```bash
/opt/lampp/xampp start
/opt/lampp/xampp stop
/opt/lampp/xampp restart
```

### Start Apache only:
```bash
/opt/lampp/xampp startapache
/opt/lampp/xampp stopapache
```

### Start Proftpd FTP server only:
```bash
/opt/lampp/xampp startftp
/opt/lampp/xampp stopftp
```

### Start MySQL Database server only:
```bash
/opt/lampp/xampp startmysql
/opt/lampp/xampp stopmysql
```

### Xampp help
```bash
/opt/lampp/xampp --help
```

### Xampp uninstall
```bash
/opt/lampp/uninstall
```