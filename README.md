residentadvisor-profile-calendar
================================

Will port your subscribed events of your public residentadvisor profile into your calendar

![Preview](/preview.jpg?raw=true "Preview")

# requirements

* you will need to have your profile public accessible in order to use this script, have a look at your profile settings for this

# installation

* 1. install and run composer with the following commands in your shell

```
curl -sS https://getcomposer.org/installer | php
php composer.phar install
```

* 2. upload the folder to a php server into its own folder, which url you can access
* 3. add the url in your ical or google calendar as a new subscription e.g. ```http://www.yourdomain.com/ra-ical/index.php?name=darkside``` while darkside is your profilename from ```http://residentadvisor.net/profile/darkside/```

# Notes

* for debugging add &debug=true to the url e.g. ```http://www.yourdomain.com/ra-ical/index.php?name=darkside&debug=true```
