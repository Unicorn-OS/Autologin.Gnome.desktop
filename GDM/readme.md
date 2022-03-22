https://vitux.com/how-to-enable-disable-automatic-login-in-ubuntu/

`sudo nano /etc/gdm3/custom.conf`

Comment out:
```
# Enabling automatic login
AutomaticLoginEnable = true
AutomaticLogin = user1
```
