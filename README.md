# wp-plugin-migrate-db-pro-media

## Important note

This plugin is unnecessary if the site is using S3 for uploads, because no images need to be migrated when migrating the database (dev, staging and production all access the same S3 bucket for a site).

## Using this plugin in a composer project

**For your project's composer.json file**
* Add this to the respositories section
```
    {
      "type": "vcs",
      "url": "https://github.com/PartnerComm/wp-plugin-migrate-db-pro-media.git"
    }
```

* Add this to the require section. Note, update the version to the latest release in the repo
```
    "pcomm/dbmigratepromedia": "1.4.14",
```
* Don't forget to separate these with commas

## Updating this plugin
* Log in to our account on [deliciousbrains.com](https://deliciousbrains.com/)
* Go to Licenses > Downloads
* Download the latest files
* Clone this repo if you don't have it locally
* Update the files in the repo with the newly downloaded files
* Commit the updates, tag it with the current plugin version number and push your changes up
