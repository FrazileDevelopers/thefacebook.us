# thefacebook.us- clone of thefacebook.com circa 2004

html by [Mark Zuckerberg](http://fb.com/zuck)

html was sourced from the wayback machine and modified to run the new back end.

# Setup

This is very messy and scattered setup. It will take customization for it to work for you.

### MySQL Setup:

- SCHEMA: /admin/SCHEMA.sql
- CREDENTIALS: /admin/classes/lib/Database.php

### Site Setup/ FB App:

All of the loading takes place in: /admin/classes/classes.php

FB and site settings are in here that need to be edited to your configuration

### Initial Setup

Login, then go into your mysql editor, and change your accountstatusid to 9 in the user table under your row

### Admin Panel:

/a/

Thanks everyone, if you can:
