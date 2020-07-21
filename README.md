# Mosco Expert

## Description

Delphi add-in that provides functionality specific to macOS and iOS development

Requires the macOS companion app for some of the functions. The full version of the Mosco macOS app is yet to be released, however the add-in also works with the MonkeyBuilder edition of the app, which can be found here:

[Monkey Builder downloads](https://www.monkeybuilder.io/download)


## Installers for the add-in

Please find installers in the bin folder. 


## Mosco functions

### Menu items

The expert adds items to the Tools menu:

![Tools Menu](./Screenshots/ToolsMenu.png)

..and to the Project Manager context menu i.e. the one that appears when you right-click a project in the Project Manager:

![Project Manager Menu](./Screenshots/PMMenu.png)


### Options

Click Mosco Options to configure the address/port for the macOS app, and for error logging

### Functions that will work only when the Mosco macOS app is running:

#### Add SDK Frameworks

Allows you to add available frameworks to the selected SDK. The following dialog is presented:

![Add SDK Frameworks](./Screenshots/AddFwks.png)

Select the desired SDK that you wish to import frameworks for, then select the desired frameworks, and click Add. 

The SDK Manager in the IDE Options is then presented. Click Update Local File Cache and click Save to complete the import

#### Show Deployed App

Opens Finder on the Mac, and shows the deployed app (if it has been deployed)

#### Create Assets.car

Creates an Assets.car file for deployment to Ad-Hoc or App Store.

To create the file, first deploy the app in Development mode, then use Create Assets.car

The Assets.car file is based upon the icon and launch images deployed with the app, and the file is placed in the Output Folder specified in the Project Options

Once the file is created, it should be added to the project in Deployment Manager (this may become automatic in the future)


### Functions that will work whether or not the Mosco macOS app is running:

#### Select Profile 

Instantly switches between connection profiles

#### Select SDK 

Instantly switches between SDKs








