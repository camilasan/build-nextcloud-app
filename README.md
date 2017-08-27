# How many lines of code do you need to build your first Nextcloud app?

## Get Nextcloud up and running
If you haven't done it already...

- How to in the [website](https://docs.nextcloud.com/server/12/developer_manual/general/devenv.html)

Quick and dirt steps:
- Download it from the [website](https://nextcloud.com/install/#instructions-server) or [github](https://docs.nextcloud.com/server/12/developer_manual/app/tutorial.html)
- If you are using git clone to get Nextcloud you also need to run:
  - git submodule init &&
  - git submodule update
- 'cd' into the folder
- Execute 'php -S localhost:8080'

## What is an app in Nextcloud

An application that adds extra functionality. For example Contacts, Calendar...

## Create the skeleton

- Go to [apps.nextcloud.com](https://apps.nextcloud.com)
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
- lib/: PHP class files (Controller)
- templates/: the templates (View)
- tests/: the tests

## The API

The most up to date code and documentation you will find on Github:

- [Nextcloud API](https://github.com/nextcloud/server/tree/master/lib/public): All the folders and files under lib/public

- [OCP\IPreview](https://github.com/nextcloud/server/blob/master/lib/public/IPreview.php): e.g. to get an image preview/thumbnail

- [OCP\Files\IRootFolder](https://github.com/nextcloud/server/blob/master/lib/public/Files/IRootFolder.php): e.g. to get the path to a file

- [The Gallery app API](https://github.com/nextcloud/gallery/wiki/RESTful-API): e.g. to create thumbnails, crop

- [HTTP](https://github.com/nextcloud/server/tree/master/lib/public/AppFramework/Http): e.g. format the response to a request


# Links
- [Generate App](https://apps.nextcloud.com/developer/apps/generate)
- [Developer Manual](https://docs.nextcloud.com/server/12/developer_manual/index.html)
- [Security Guidelines](https://docs.nextcloud.com/server/12/developer_manual/general/security.html)
- [Coding Style Guidelines](https://docs.nextcloud.com/server/12/developer_manual/general/codingguidelines.html)
- [Nextcloud API](https://doc.owncloud.org/api/namespaces/OCP.html)

