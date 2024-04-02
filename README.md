# [Sample plug-in: Table User Count Plug-in]
## Purpose of the Sample Plug-in
This sample plug-in is available for educational purposes.  
Use this plug-in to understand how Kintone plug-ins work, and how they are structured.
A non-packaged version written with a single JavaScript file can be found here https://kintone.dev/en/tutorials/count-record-content/count-the-number-of-users-in-tables/

## What the plug-in does
This plug-in counts the number of times a user is listed inside a table, and places that number into a given field when the record data is saved.

## Plug-in directory structure
This sample plug-in is created with the following directory structure.


src/  
├── html/  
│        └──── config.html  
├── css/  
│        ├──── 51-modern-default.css  
│        ├──── config.css  
│        └──── kintone-ui-component.min.css  
├── js/  
│        ├──── config.js  
│        ├──── desktop.js  
│        └──── kintone-ui-component.min.js  
├── image/  
│        └──── people.png  
└── manifest.json  

## How to use
To simply test out the plug-in on your Kintone domain, follow these steps:

1. Download the plug-in zip file  
Reference: https://github.com/kintone/SAMPLE-Date-input-button-Plug-in/releases
2. Install the plug-in into your domain  
Reference: https://get.kintone.help/hc/en-us/articles/115001519707-Installing-Viewing-Plug-ins
3. Add the plug-in to a specific Kintone App  
Reference: https://get.kintone.help/hc/en-us/articles/115001511188-Adding-Plug-ins-to-an-App
4. Make sure that at least one Number field and a Table with a User Selection field are placed in the form of your Kintone App. Access the plug-in settings, and set up the necessary settings. Save the settings, and update the App.
5. Create a new record and make as many rows in the table as you would like, filling in the User Selection field. Save the record. The number of times the specified user has been entered into the User Selection fields in the table will appear in the Number field.

## How to modify
1. Fork to your repo
2. Make changes to files under /src
3. Repackage the plug-in by:  
 i. Zipping the manifest.json file, css directory, html directory, image directory and js directory into one zip file.  
 ii. Drag and dropping the file into the [kintone plug-in packer](https://kintone.dev/en/plugins/plug-in-tool-guides/package-plug-in-files-using-plugin-packer/).

## Pull Request Policy
As this repo exists for educational purposes, we will most likely turn down pull requests that contain updates with new features.  
Please feel free to host plug-ins with new features on your own repository.  
Bug fixes are happily accepted.
