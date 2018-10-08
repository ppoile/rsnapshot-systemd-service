systemd service for rsnapshot
=============================

1. install rsnapshot
2. adapt /etc/rsnapshot.conf
3. install and enable rsnapshot-backup service:
   $ sudo cp rsnapshot-backup.service /etc/systemd/system/
   $ sudo systemctl enable rsnapshot-backup.service
