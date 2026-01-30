 # Employee-Recs

## Overview

The Employee Recs module is the first module of the SyncField project. This module allows administrators to manage Employee Training Records and Partner (Contractor) records efficiently. 
Admin users can search, view, update, and manage employee or partner details from a single screen.

    
##  Employee Training Records Screen

This screen displays the complete list of employees or partners along with their associated training records and profile information.

  <img width="1900" height="950" alt="image" src="https://github.com/user-attachments/assets/9a6424ba-b60c-4385-b22b-c584fbf46410" />


The screen is divided into two main sections:
  * Left Panel – Search and filter options
  * Right Panel – Selected employee or partner details

### Left Panel: Employee / Partner List

**Employee List Features**

Admins can search and filter employees using the following options:

* Group
* Employee Name
* Supervisor
* Employee Status (Active / Inactive)

**Additional actions:**

* View total employee count
* Add a New Employee using the New Employee button

**Partner List Features**

Admins can switch to the Partners tab and search partner records using:

* Company
* Partner Name
* Supervisor
* Status

### Right Panel: Employee / Partner Details

When an admin selects an employee or partner from the left panel, detailed information is displayed on the right side of the screen.

Displayed information includes:

* Employee / Partner Name
* Employee / Sync Number
* Group
* Role 
* Security Role
* Supervisor
* Department
* Job Type
* Training Plan
* Profile Image

#### Available Actions

The following action buttons are available for the selected employee or partner:

1. View Details
   
* Employee: Opens the Employee Details screen where admin can view or edit employee information.
   <img width="1020" height="729" alt="image" src="https://github.com/user-attachments/assets/c4480520-79cf-4b32-9159-31d92c9c134e" />

* Partner (Contractor): Displays the message: `This individual is a Partner Worker (Contractor). To make changes to their details, go to the Partners tab from the menu and then to Worker Details.`

2. Change Status
  * Allows the admin to change the employee or partner status (e.g., Active, Inactive, Terminated).
     <img width="570" height="163" alt="image" src="https://github.com/user-attachments/assets/db77b391-5a76-4848-8dea-4516fb8c9f1a" />

3. Change Security  
  * Enables updating the Security Role of the selected employee (e.g., Admin, Senior Trainer etc).
     <img width="567" height="176" alt="image" src="https://github.com/user-attachments/assets/44add438-e639-4f18-9219-9729c1a29dd7" />

4. Transfer
  * Allows the admin to transfer the employee to a different Site or Group.
     <img width="407" height="228" alt="image" src="https://github.com/user-attachments/assets/7567f4dd-f8c4-4539-860c-dffffbb5a068" />

5. Trainer Rights
  * Admins can assign or remove trainer-related permissions: 
    * Override OK
    * Blue Card Holder
      <img width="571" height="143" alt="image" src="https://github.com/user-attachments/assets/90139501-e754-4f9e-86c0-c468298e0b07" />

6. Change Image
  * Allows updating the employee or partner profile image.
       <img width="811" height="221" alt="image" src="https://github.com/user-attachments/assets/bb12cece-2714-415d-9244-41220a9a6106" />


#### Training Records Section

**Training Records Section**
Below the employee details, training records are displayed in a tabular format.

Information includes:
* Training Number
* Training Title
* Category
* Certification Date
* Expiry Date
* Source
* Site
* Training Type

Available actions:

* Get Report – Generate training reports
* Add Record – Add a new training record
* Deactivate – Deactivate selected training records

## Key Notes

* All data updates reflect after saving.
* Admin users can manage both employees and partners from the same module.
* Partner details are restricted and editable only from the Partners module.
