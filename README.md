residentadvisor-profile-calendar
================================

Will port your subscribed events of your public residentadvisor profile into your calendar

# requirements

* you will need to have your profile public accessible in order to use this script

# installation

* install and run composer

```
curl -sS https://getcomposer.org/installer | php
php composer.phar install
```

* upload the folder to a php server into its own folder
* subscribe the url in your ical or google calendar e.g. 'http://www.yourdomain.com/ra-ical/index.php?name=darkside'

# Notes

* for debugging add ?debug=true to the url
