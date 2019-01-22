# Mendix Bootstrap Input Addons Widget

This widget makes it possible to select multiple files at the same time and upload them to mendix.

To use the widget, place it in a Entity context (like a dataview) and configure the widget's properties.

## Features
* (Optional) limit the file size of the files that are being uploaded (in kilobytes)
* (Optional) limit the filetype to a comma seperated value example: jpg,jpeg,png
* Select multiple files in the file selector window
* onChange events

## Limitations
* validation message when max file size exceeded display's wrong size of the uploaded files.

For any request or bug please create an issue at [GitHub](https://github.com/JAM-IT-NL/JamUploadIt).

# Build project
* npm install
* gulp build

# Updating
* To update all dev dependencies in package.json: 
** npm install -g npm-check-updates
** npm-check-updates -u