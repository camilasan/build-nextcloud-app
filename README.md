# How many lines of code do you need to build your first Nextcloud app?

## Get Nextcloud up and running
If you haven't done it already...

Quick and dirt steps:
- Download it from the [website](https://nextcloud.com/install/#instructions-server) or [github](https://github.com/nextcloud/server)
- 'cd' into the folder
- Execute 'php -S localhost:8080'

## What is an app in Nextcloud

An application that adds extra functionality. For example Contacts, Calendar...

## Create the skeleton

- Go to the apps store at [apps.nextcloud.com](https://apps.nextcloud.com)
- Menu 'App Developer'
- Click on 'Generate app'
- Fill up the form
- Download the skeleton

## Add your app to Nextcloud

- Copy the skeleton to the 'apps' folder in your Nextcloud
- Access Nextcloud in the browser
- On your avatar menu
- Click on '+ Apps'
- Your app will be listed in 'Disabled apps'

# App skeleton
- appinfo/: app metadata and configuration
- css/: the CSS
- js/: JavaScript files
- lib/: PHP class files
- templates/: the templates (View)
- tests/: the tests

# Links
- [Nextcloud apps](https://apps.nextcloud.com/developer/apps/generate)
- [Developer Manual] (https://docs.nextcloud.com/server/12/developer_manual/index.html)
- [Nextcloud API](https://doc.owncloud.org/api/namespaces/OCP.html)

