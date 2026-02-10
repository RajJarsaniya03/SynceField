# SyncField Desktop Application Documentation
## Overview

The SyncField Desktop Application is a standalone desktop-based version of the SyncField system designed to allow users to manage training, employee records, campaigns, task codes, and content reviews directly from their local machine.

This application is designed to work in both Online Mode and Offline Mode, providing flexibility for users who may need to operate in environments with limited or no internet connectivity.

The desktop application synchronizes data with the SyncField Web Application to ensure consistency between platforms.

## Application Modes

1. Online Mode
    * The application is connected to the internet.
    * All updates are synced with the SyncField Web Application.
    * Users can access the latest available data from the server.

2. Offline Mode
    * The application works without internet connectivity.
    * Users can continue performing actions locally.
    * All changes are stored in the local database.
    * Once internet is available, data can be synced with the web application.

The current working mode is displayed at the top-right corner of the application interface.


## Sync Functionality

A dedicated Sync Process is available in the desktop application to maintain data consistency between the desktop and web platforms.

### How Sync Works

* When the user starts the sync process, the application checks for updates.
* Any new or modified data in the desktop application is uploaded to the SyncField Web Application.
* Any updates made in the web application are downloaded to the desktop application.
* This ensures both systems remain up to date.

### Full Sync Option

From the Settings button (available in the top-right corner), users can access an additional option called:

`Begin Full Sync`

* When this option is selected, the application creates a fresh new local database.
* All data is downloaded again from the server.
* This is useful when data inconsistencies occur or when a clean resynchronization is required.

## Help and Guides

The application includes a built-in help section called `Sync Safety System Guides`, which provides useful documentation for users.

Available guides include:

* Sync Help Guides
* Company Guides
* Admin Guides

Each section contains detailed help topics to assist users in understanding and operating the system effectively.

## Desktop Application Modules

The following main menu options are available in the SyncField Desktop Application:

* Home Page
* Employee
* Task Codes
* Campaigns
* Annual Recert
* Training
* Content Review
  
Each module is explained in detail below.

### Home Page

