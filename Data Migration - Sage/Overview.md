Overview
========

Data Migration – Sage from Technology Management extends the functionality of
Dynamics 365 for Financials’ Data Migration wizard. The additional capability
allows you to export your data from your Sage Line 50 installation and import
into Dynamics 365 for Financials.

Process
=======

The data migration process is split into the following steps:

1.  Install the Data Migration – Sage extension

2.  Open the Data Migration page in Dynamics 365 for Financials

3.  Select “Sage (UK)” as the data source

4.  Download our utility to extract data from your Sage Line 50 installation and
    create a zip file that you can upload to Dynamics 365 for Financials

5.  Select the appropriate Customer, Vendor and Item templates to use when
    importing your data

6.  Select the zip file created above to upload your data to Dynamics 365 for
    Financials.

7.  Review the number of records that have been read and select which entities
    to import.

8.  Review and post the sales and purchase journals that have been created

Data Migration Wizard
=====================

Data Source Selection
---------------------

The Data Migration Wizard is a page in Dynamics 365 for Financials that helps
you to migrate data from a legacy system. The first step of the wizard asks you
to select a data source. Choose “Sage (UK)”.

Data Extract Utility
--------------------

The next page of the wizard has buttons to **Download Template** and access
**Settings.**

Click the **Download Template** button to download and install our utility that
will help you to extract data from your Sage installation in a format that can
be uploaded to and read by Dynamics 365 for Financials.

Select the Sage data folder, company and the path to export the data to. The
utility will create a zip folder of the extracted data which will be uploaded in
the next stage of the Data Migration Wizard.

Data Migration Settings
-----------------------

Click the **Settings** button to open the “Data Migration Settings” page. This
page allows you to select a template for Customers, Vendor and Items that are
imported from Sage. Various templates are available by default in Dynamics 365
for Financials for you to choose from. Templates must be selected for each
entity before you can continue with the Data Migration Wizard.

File Selection
--------------

On the next stage of the wizard you will be prompted to select a file to upload.
Select the zip file that was created above. The extension will read the data
from the extracted zip files and display the “No. of Records” for each of the
record types. (Un)tick the records that you wish to import and click the
**Import** button.

Migration Errors
================

Your data is passed through a “Configuration Package” in Dynamics 365 for
Financials. This is to check that the data is valid before importing. Any
records that contain invalid data will be visible in the package and will be
displayed automatically after the data is imported.

You can also access the imported data in the configuration package by searching
for **“Sage Migration Data”** in the menu.

Displaying Validation Errors
----------------------------

Click on the **“No. of Package Errors”** column – the figure will be highlighted
in red. The “Config. Package Records” page will be opened to display the data
that has been imported. Click on the **Show Error** button at the top of the
page to see the error that was encountered in applying the selected record.

Correcting Data
---------------

The data in the “Config. Package Records” page is editable. Having displayed the
validation error message you can edit the data to correct it. When you have
finished editing some data the record is revalidated. If there are no more
validation errors the record will disappear from the page.

If you do not want to import a record you can delete the record from the
“Config. Package Records” page.

Applying Data
-------------

When you have corrected the validation errors you can import the corrected data
with the **Apply Package** button at the top of the page.

Journals
========

A journal will be created for the opening balances of sales and purchase
documents. Review, edit and post these journals to create the opening balances
for your customers and vendors.

Sales Journal
-------------

Search for **Sales Journals** in the menu and open the **SAGE-SALE** batch. You
may need to change the Batch Name at the top of the page if it has been opened
to a different batch. Once you have reviewed the data that has been imported,
post the batch with the **Post** button.

Purchase Journal
----------------

Search for **Purchase Journals** in the menu and open the **SAGE-PURCH** batch.
You may need to change the Batch Name at the top of the page if it has been
opened to a different batch. Once you have reviewed the data that has been
imported, post the batch with the **Post** button.
