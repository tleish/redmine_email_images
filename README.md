[![Maintained? No](https://img.shields.io/badge/maintained%3F-no!-red.svg)](https://shields.io/)
# THIS FORK IS NO LONGER MAINTAINED

* * *

# Redmine Email Images

The plugin address this issue: http://www.redmine.org/issues/2770. 

## Description

Email clients are not logged in and can't load images in email notifications
from redmine. You can either allow downloading attachments for anonymous
users or include images as attachments in email. This plugin uses second 
approach.

## Installation

To install the plugin clone the repo from github and migrate the database:

```
cd /path/to/redmine/
git clone git://github.com/dkalachov/redmine_email_images.git plugins/redmine_email_images
bundle
rake redmine:plugins:migrate RAILS_ENV=production
```

## Compatibility

The latest version of this plugin is only tested with Redmine 2.6-stable and 3.0-stable.

