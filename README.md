# automatically add Host-tracker agent ips to csf whitelist

add this content to a file in /etc/cron.daily with 777 permission
this file run every day by cron job and if had any new ips in host-tracker agent which this not exist in your whitelist automatically added it to csf whitelist
