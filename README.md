# backup config switch 3650
python backup runing and startup config switch cisco 3650 realtime to tftp server and rsync file config to nas datastore 
command add to /etc/crontab
0 23 * * * root /home/script-backup-switch/run-backup-config-switch.sh >> /home/script-backup-switch/log-backup-config-switch 2>&1
