<div align="center">
<h1> PROJECT NUMA <br>
DISCOVERY BOOK</h1>
</div>

## Index
1. [Introduction](#introduction)  
2. [Objectives](#objectives)  
3. [Functionalities](#funcs)  
        3.1 [Header](#header)  
        3.2 [Sidebar](#sidebar)  
        3.3 [Data display](#data)  
        3.4 [Data manipulation](#manipulation)  
        &emsp; 3.4.1 [Creating folders and dashboards](#create)  
        &emsp; 3.4.2 [Editing folders and dashboards](#edit)  
        &emsp; 3.4.3 [Delete folders and dashboards](#delete)  
        &emsp; 3.4.4 [Search](#search)  
        3.5 [Security and API connection](#api)

4. [Resources](#resources)  
        4.1 [Prerequisites](#prerequisites)  
        4.2 [Download the project](#download)  
        4.3 [Serve the project](#serve)  


<a name="introduction"></a>
## **1. Introduction**
This is a guide for the Front-End of the project "Discovery Book" developed by Padawan Team during Numa 6.0. Please remember to check the [*Back-End Readme*](https://www.google.es).

<a name="objectives"></a>
## **2. Objectives**
Design an atractive and intuitive interface for users usage. The design of the user interface follows the standard of the company, so the navigation flows in a natural way. We have implemented a CRUD that allow the user creating, editing and deleting folders or dashboards (considering the permissions of the user). This requires the connection with the Back-End's endpoints to make the changes last.

<a name="funcs"></a>
## **3. Functionalities**

<a name="header"></a>
### **3.1 Header**
As mentioned before, we have designed the header following the standard of the company.

![header](/img/header.png "Web header")


<a name="sidebar"></a>
### **3.2 Sidebar**
The sidebar contains the navigation feature along the folders. Selecting a folder, it expands showing its content (if it has). The content is also shown in the data display area (detailed in the next section). It can also be collapsed, so the data display area fits a bigger area.

Sidebar navigation

![sidebar-n](/img/sidebar-navigate.png "Sidebar navigate")

Collapsed sidebar

![sidebar-c](/img/sidebar-collapsed.png "Sidebar collapsed")


<a name="data"></a>
### **3.3 Data Display**
To the right of the sidebar we can find the data display area. Here is shown the content of the folders (if there is no content, a "Zero page" its shown indicating this situation).

Folder with content

![folder-c](/img/folder-w-content.png "Folder with content")

Empty folder

![folder-e](/img/empty-folder.png "Empty folder")


<a name="manipulation"></a>
### **3.4 Data Manipulation**

<a name="create"></a>
#### **3.4.1 Creating folders/dashboards"**
As we saw in the previous section, there is a "New" button. If it is clicked, it appears an interface with a form to indicate the folder/dashboard name and description.

Create new folder interface

![create-f](/img/create-f.png "Create new folder")

Create new dashboard interface

![create-d](/img/create-d.png "Create new dashboard")


<a name="edit"></a>
#### 3.4.2 Editing folders/dashboards"
In the body of the project we find a table where we can see the different contents of a folder. It can be a folder or a dashboard. Inside an element we can find three points at the right side of the row. When we click on it, we will see some actions to perform, one of them is the "edit" action. This part is exactly the same as the creating one. The only difference is that the data of the folder/dashboard we are editing will be shown in the interface text boxes.

Edit new folder interface

![edit-f](/img/edit-f.png "Edit new folder")

Edit new dashboard interface

![edit-d](/img/edit-d.png "Edit new dashboard")


<a name="delete"></a>
### 3.4.3 Delete folders/dashboards 
We can delete folders/dashboards by clicking ons the three points we explainted in the previous section, and seleting "Delete".

![delete-element](/img/delete-element.png "Delete element")

If we click on delete we will get an alert, so we can confirm if we want to delete it or not. 

![delete-element-confirm](/img/delete-element-confirm.png "Delete element confirm")


<a name=""></a>
<a name=""></a>
<a name=""></a>
<a name=""></a>
<a name=""></a>
<a name=""></a>
<a name=""></a>
<a name=""></a>

<a name="prerequisites"></a> 
### **4.1 Prerequisites**
In order to be able to use the project we need:
* A code editor, we recommend using Visual Studio Code.
* We need to have angular cli installed and node js.
* In order to run the project properly and not get permissions or connectivity errors, you must go to [Back](https://github.com/Stratio/governance-dashboards-drive) to    download and implement the part of the back, in the repository it is contemplated and  its installation is detailed.

<a name="download"></a>
### **4.2 Download the project**
To download the project you have 2 ways:
* The first one is the simplest but the bad.  
        - Go to the [project's repository](https://github.com/Stratio/governance-dashboards-drive-ui) in Github. In the upper left part of the container where the project is, it is shown a green button (code). If you click on it a tab will appear, in the lower part click on download zip and a zip of the project will be downloaded.
* The second is the best option because we can play with the git infrastructure.  
        - For this we need to have git installed on the pc.  
        - Create a parent folder and inside it 2 children: front and back.  
        - Go into the front folder and check that it is empty.  
        - Clone the repository we use the command:

>``git clone git@github.com:Stratio/governance-dashboards-drive-ui.git``
     
<a name="serve"></a>
### **4.3 Serve the project**
To launch the project locally, the first thing to do is to compile the project. To do that, we need a terminal/console located in the project's folder. Then, we have to execute the following command:

>``npm install``

If it does not compile correctly, use the same command with the --force after it.

>``npm install --force``

In order to launch it from within the project, we use the following command:

>``ng serve -o``


