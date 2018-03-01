# CKL Advanced Line Recognition #

## Introduction ##
This repository contains an extension for [Continia Document Capture](http://continia.com/documentcapture-for-dynamics-nav.aspx) module, which is a solution for scanning of invoices and other documents directly from Microsoft Dynamics NAV! 

The initial development was done by CKL Software GmbH (CKL) and the code will be maintained by CKL regularly based on experiences made in future projects.

At the moment there is no other documentation than this readme file. 

**Please report issues in the issues list.**

## Implementation of the extension ##
Please note that the code is based on Microsoft Dynamics NAV 2016 RTM database and an installed version of Document Capture Version 4.50.01


1. Clone the project / Download all  *.txt files to your client
2. Import all txt files into your database via the development environment 
3. Filter the versionlist for *CKL and compile all objects

## How to use the extension ##
The concept of the Advanced Line Recognition extension is to identify at least one field per line by Document Capture standard code - we'll call this field "line identification field" (LIF) in this guide.

Based on the position of this field the user will define the "offset" of other fields that he wants to capture. 

1. Open Dynamics NAV Client
2. Import open Documents to Document Capture
3. Open the Document Journal
4. Run Recognize Fields action from the menu to recognize the fields of the selected document
5. Open the Document Card from the menu
6. Capture the LIF
7. 
