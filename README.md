# thermy-autoupdate

Trigger this automatic update script by editing root crontab with:
  sudo crontab -e -u root
Add this line to the end of the crontab
@reboot /<path to script>/thermy-autoupdate/update
