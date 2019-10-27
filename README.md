# CPanel configuration script

This script installs and configures cPanel according to the best practices.

## Installation

```bash
wget https://raw.githubusercontent.com/diyarit/Cpanel-Config/master/install_cpanel.sh -O ./install_cpanel.sh && bash install_cpanel.sh
```

## NOTE: Install only on CentOS 7 Minimal

## Tasks that you perform:

#### 1-Network Configuration Optimization.
#### 2-Configure the DNS.
#### 3-Install the "Base" package and other recommended ones.
#### 4-SSH configuration optimization.
#### 5-Install cPanel if it does not detect it.
#### 6-Configure Tweak Settings with recommended values.
#### 7-Configure AWStats as a statistics system.
#### 8-Disable compilers.
#### 9-Configure minimum password complexity.
#### 10-Enable php open_basedir protection.
#### 11-Disable Shell Fork Bomb Protection (generates problems with limits on servers with high consumption).
#### 12-Disable SMTP Restrictions (after using SMTP_BLOCK from CSF).
#### 13-Configure Apache with recommended values.
#### 14-Configure Exim with recommended values.
#### 15-Configure Pro-FTPd with the recommended values.
#### 16-Configure the "disabled" and "default" features with the recommended values.
#### 17-Install and configure CSF Firewall with recommended values.
#### 18-Configure recommended MySQL settings.
#### 19-Configure all php.ini with the recommended values.
#### 20-Create the "default" package with the recommended values.
#### 21-Synchronize the server time with an NTP server.
