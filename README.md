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
        3.5 [API connection](#api)

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


<a name=""></a>
<a name=""></a>


