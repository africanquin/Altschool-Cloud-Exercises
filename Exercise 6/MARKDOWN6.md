### Review and implement at least 10 CSI benchmark recommendations for Ubuntu 
<br>

#### 1. Ensure remote login warning banner is configured properly
This allows the contents of the /etc/issue.net file to be displayed to users prior to login for remote connections from configured services.

![remote login](./Remote%20login%20warning%20banner.png "Remote login warning banner")

### 2. Ensure GPG keys are configured
This is used to verify that GPG keys are configured correctly for your package manager

![GPG Keys](./GPG%20Keys.png "GPG Keys")

### 3. Ensure iptables-persistent is not installed with ufw
Running both ufw and the services included in the iptables-persistent package may lead to conflict. This command is to verify that the "iptables-persistent" package is not installed

![iptables-persistent is not installed with ufw](./iptables%20persistent%20is%20not%20installed%20with%20ufw.png "iptables-persistent is not installed with ufw")

### 4. Ensure ufw is installed
This is to verify that Uncomplicated Firewall (UFW) is installed

![ufw installed](./ufw%20installed.png "ufw installed")

### 5. Ensure auditd service is enabled and active
System events provides system administrators with information to allow them to determine if unauthorized access to their system is occurring.
Run the following commands to verify auditd is enabled and active

![auditd service is enabled and active](./auditd%20service%20is%20enabled%20and%20active.png "auditd service is enabled and active")

### 6. Ensure auditd is installed
The following command is run to verify auditd and audispd-plugins are installed

![verify auditd and audispd-plugins](./verify%20auditd%20and%20audispd-plugins.png "verify auditd and audispd-plugins")

The following command is run to install and confirm auditd

![install auditd and audispd-plugins](./install%20auditd%20and%20audispd-plugins.png "install auditd and audispd-plugins")

![confirm auditd and audispd-plugins](./confirm%20auditd%20and%20audispd-plugins.png "confirm auditd and audispd-plugins")

### 7. Ensure audit log storage size is configured
This shows the maximum size of the audit log file before a new log file will be started. It is important to set an appropriate size for the log files. The default value is 8MB

![audit log storage size](./audit%20log%20storage%20size.png "audit log storage size")

### 8. Ensure SSH PAM is enabled
This will enable PAM authentication using. This is important if you want to restrict access to services based off of IP, time or other factors of the account

![Enable SSH PAM](./confirm%20auditd%20and%20audispd-plugins.png "Enable SSH PAM")

### 9. Ensure SSH LogLevel is appropriate
This specify the logging levels for SSH users

![SSH LogLevel](./SSH%20log%20level.png "SSH LogLevel")

### 10. Ensure SSH HostbasedAuthentication is disabled
This provides an additional layer of protection by disabling the ability to use .rhosts files in SSH 

![SSH HostbasedAuthentication disabled](./SSH%20HostbasedAuthentication%20disabled.png "SSH HostbasedAuthentication disabled")