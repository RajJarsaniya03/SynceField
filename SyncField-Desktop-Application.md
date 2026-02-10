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

## Home Page

**Notifications Section**
* All important notifications are displayed on this page in a tabular format.
* Notification types available on the left panel include:

**a. Campaigns Notification**

* Displays campaign-related alerts.
* Clicking on this notification navigates the user to the `Campaigns` page.

**b. Classes**

* Opens a pop-up window titled: `Class: Sync Annual Refresher Training`.
* Displays class-related participant details.

**c. Training Tracker**

* Clicking on this notification type navigates the user to the `Training Tracker` page.


**d. Content Reviews (SOPs)**

* Clicking this notification type takes the user to the `Content Reviews` page.

**e. Task Codes**

* Clicking this notification type takes the user to the `Content Reviews` page.

## Employee Module

When the user selects Employee from the main menu, the system opens the `Employee Training Records` page.

**Features**

* Displays completed training records for employees.
* Various filters are available to easily locate employee information.

  *  Users can view:
      * Employee details
      * Training history
      * Certification status

All employee-related updates received through sync are reflected in this module.

## Task Codes Module

The Task Codes module displays all task code-related information.

**Key Features**

* Users can search and filter task codes.
* For a selected task code, the following details are available:
   * Assignments
   * PreRequisites (PreReqs)
   * Skills
   * Checklist
   * Pre-Operational (PreOp) information

**Certified Workers List**
   * Shows employees certified under the selected task code.

**Equipment Details**
   * Displays equipment records associated with the selected task code.

## Campaigns Module

The Campaigns page manages all campaign-related activities.

**Displayed Information**

* Campaign List
* Selected Campaign Details
* Participants of the selected campaign
* Required content reviews
* Signature panel

**Filters Available**

* My Employees
* All Employees
  
**Signature Process**

* Users can sign for participants.
* After submitting a signature, the participant status changes from: Pending → Completed

## Annual Recert Module

The Annual Recert page is directly related to campaigns.

Purpose

* Used for managing annual recertification processes.
* Displays recertification campaigns and employee participation.
* Allows administrators to manage annual certification workflows.

## Training Module

The Training page displays all scheduled training activities.

**Features**

* View scheduled training list
* Start selected scheduled training
* Create new training (similar to web application functionality)

This module helps trainers and administrators manage training execution directly from the desktop application.


## Content Review Module

The Content Review page allows users to manage SOP and document reviews

**Features**

* Displays list of all available content
* Employee-wise certification creation
* Signature functionality for content acknowledgment

This module ensures that required documents and procedures are properly reviewed and acknowledged by employees.

## Conclusion

The SyncField Desktop Application provides a powerful and flexible platform for managing employee training, certifications, campaigns, and compliance activities. With robust synchronization capabilities and offline support, it ensures uninterrupted workflow and accurate data management across both desktop and web environments.
