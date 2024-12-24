
# Remove Asterisk
```
rm -rf /etc/asterisk
rm -f /etc/dahdi.conf
rm -rf /var/log/asterisk
rm -rf /var/lib/asterisk
rm -rf /var/spool/asterisk
rm -rf /usr/lib/asterisk

```

# Remove FreePBX
```
rm /usr/sbin/amportal
rm -rf /var/lib/asterisk/bin/*
rm -rf /var/www/html/*
rm /etc/amportal.conf
rm /etc/asterisk/amportal.conf
rm /etc/freepbx.conf
rm /etc/asterisk/freepbx.conf
rm -f /etc/asterisk/*.conf
