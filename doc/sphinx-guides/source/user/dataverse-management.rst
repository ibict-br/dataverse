Dataverse Management
++++++++++++++++++++++++++++

A dataverse is a container for datasets (research data, code, documentation, and metadata) and other dataverses, 
which can be setup for individual researchers, departments, journals and organizations.

|image1|

Once a user creates a dataverse they, by default, become the
administrator of that dataverse. The dataverse administrator has access
to manage the settings described in this guide.

Create a Dataverse (within the "root" Dataverse)
===================================================

Creating a dataverse is easy but first you must be a registered user (see Create Account).

#. Once you are logged in click on the "Add Data" button and in the dropdown menu select "New Dataverse".
#. Once on the "New Dataverse" page fill in the following fields:
    * **Name**: Enter the name of your dataverse.
    * **Identifier**: This is an abbreviation, usually lower-case, that becomes part of the URL for the new dataverse. Special characters (~,\`, !, @, #, $, %, ^, &, and \*) and spaces are not allowed. **Note**: if you change the Dataverse URL field, the URL for your Dataverse changes (http//.../'url'), which affects links to this page.
    * **Email**: This is the email address that will be used as the contact for this particular dataverse. You can have more than one contact email address for your dataverse.
    * **Affiliation**: Add any Affiliation that can be associated to this particular dataverse (e.g., project name, institute name, department name, journal name, etc). This is automatically filled out if you have added an affiliation for your user account.
    * **Description**: Provide a description of this dataverse. This will display on the home page of your dataverse and in the search result list.
    * **Category**: Select a category that best describes the type of dataverse this will be. For example, if this is a dataverse for an individual researcher's datasets, select Researcher. If this is a dataverse for an institution, select Organization & Institution.
    * **Choose the sets of Metadata Elements for datasets in this dataverse**: by default the metadata elements will be from the host dataverse that this new dataverse is created in. Dataverse offers metadata standards for multiple domains. To learn more about the metadata standards in Dataverse please check out the appendix (insert link here)
    * **Select facets for this dataverse**: by default the facets that will appear on your dataverse landing page will be from the host dataverse that this new dataverse was created in. The facets are simply metadata fields that can be used to help others easily find dataverses and datasets within this dataverse. You can select as many facets as you would like.
#. Selected metadata elements are also used to pick which metadata fields you would like to use for creating templates for your datasets. Metadata fields can be hidden, or selected as required or optional. Once you have selected all the fields you would like to use, you can create your template(s) after you finish creating your dataverse.
#. Click "Create Dataverse" button and you're done! 

\*Required fields are denoted by a red asterisk.

Edit Dataverse 
=================

To edit your dataverse, navigate to your dataverse homepage and select the "Edit Dataverse" button, 
where you will be presented with the following editing options: 

- :ref:`General Information <general-information>` : edit name, host dataverse, alias, email, 
  description, affilitation, Metadata Elements, and facets for your dataverse.
- :ref:`Theme + Widgets <theme-widgets>` : upload a logo for your dataverse, add a link to your department or personal website, and select colors for your dataverse in order to brand it. Also, you can get code to add to your website to have your dataverse display on it.
- :ref:`Permissions <dataverse-permissions>` : give Dataverse users permissions to your dataverse, i.e.-can edit datasets, and see which users already have which permissions for your dataverse
- :ref:`Dataset Templates <dataset-templates>` : these are useful when you have several datasets that have the same information in multiple metadata fields that you would prefer not to have to keep manually typing in
- :ref:`Dataset Guestbooks <dataset-guestbooks>` : 
- :ref:`Featured Dataverses <featured-dataverses>` : if you have one or more dataverses, you can use this option to show them at the top of your dataverse page to help others easily find interesting or important dataverses
- **Delete Dataverse**: you are able to delete your dataverse as long as it is not published and does not have any draft datasets 

.. _general-information:

General Information
=====================================================

The General Information page is how you edit the information you filled in while creating your dataverse. If you need to change or add a contact email address, this is the place to do it. Additionally, you can update the metadata elements used for datasets within the dataverse, change which metadafields are hidden, required, or optional, and update the facets you would like displayed for browsing the dataverse. If you plan on using templates, you need to select the metadata fields on the General Information page.

Tip: The metadata fields you select as required, will appear on the Create Dataset form when someone goes to add a dataset to the dataverse. 

.. _theme-widgets:

Theme + Widgets
====================================================

The Theme + Widgets feature provides you with a way to customize the look of your dataverse as well as provide code for you to put on your personal website to have your dataverse appear there. (For adding your dataverse to an OpenScholar site, follow these instructions.)

For Theme, you can decide either to use the customization from the dataverse above yours or upload your own image file. Additionally, you can select the colors for the header of your dataverse and the text that appears in your dataverse. You can also add a link to your personal website, the website for your organization or institution, your department, journal, etc.

There are two options for Widgets, a Dataverse Search box widget and a Dataverse Listing widget. The Dataverse Search Box will add a search box to your website that when someone enters a search term in and clicks Find, will bring them to Dataverse to see the results. The Dataverse Listing widget will provide a listing of all your dataverses and datasets. When someone clicks on a dataverse or dataset in the widget, it will bring them to your dataverse to see the actual data. Within the Widgets page, you can copy and paste the code for the widget you would like to have on your website. 

Adding Widgets to an OpenScholar Website



.. _dataverse-permissions:

Permissions 
=======================================================
When you access a dataverse's permissions page, you will see there are three sections: Permissions, Users/Groups, and Roles. 

|image2|
Clicking on Permissions will bring you to this page:
|image3|
By clicking on the Edit Access button, you are able to change the settings allowing no one or anyone to add either dataverses or datasets to a dataverse.
|image4|
The Edit Access pop up allows you to also select if someone adding a dataset to this dataverse should be allowed to publish it (Curator role) or if the dataset will be submitted to the administrator of this dataverse to be reviewed then published (Contributor role). These Access settings can be changed at any time.

Assigning a role
-----------------------
You can also give access to a Dataverse user to allow them to access an unpublished dataverse as well as other roles. To do this, click on the Assign Roles to Users/Groups button in the Users/Groups section. You can also give multiple users the same role at one time.
|image5|
|image6|
This roles can be removed at any time.


.. _dataset-templates: 

Dataset Templates
======================
Templates are useful when you have several datasets that have the same information in multiple metadata fields that you would prefer not to have to keep manually typing in. In Dataverse 4.0, templates are created at the dataverse level, can be deleted (so it does not show for future datasets), set to default (not required), and can be copied so you do not have to start over when creating a new template with similiar metadata from another template. When a template is deleted, it does not impact the datasets that have used the template already.

How do you create a template? 

#. Navigate to your dataverse, click on the Edit Dataverse button and select Dataset Templates. 
#. Once you have clicked on Dataset Templates, you will be brought to the Dataset Templates page. On this page, you can 1) decide to use the dataset templates from your parent dataverse 2) create a new dataset template or 3) do both.
#. Click on the Create Dataset Template to get started. You will see that the template is the same as the create dataset page with an additional field at the top of the page to add a name for the template.
#. After adding information into the metadata fields you have information for and clicking save, you will be brought back to the Manage Dataset Templates page and should see your template listed there now with several options. 
#. A dataverse does not have to have a default template and users can select which template they would like to use while on the Create Dataset page. 
#. You can also click on the View button on the Manage Dataset Templates page to see what metadata fields have information filled in.

\* Please note that the ability to choose which metadata fields are hidden, required, or optional is done on the General Information page for the dataverse.

.. _dataset-guestbooks:

Dataset Guestbooks
===========================================================
Guestbooks allow you to collect data about who is downloading the files from your datasets. You can decide to collect account information (username, given name & last name, affiliation, etc.) as well as create custom questions (e.g., What do you plan to use this data for?). You are also able to download the data collected from the enabled guestbooks as Excel files to store and use outside of Dataverse.

How do you create a guestbook?

#. After creating a dataverse, click on the Edit Dataverse button and select Dataset Guestbook
#. By default, guestbooks created in the dataverse your dataverse is in, will appear. If you do not want to use or see those guestbooks, uncheck the checkbox that says Include Guestbooks from Root Dataverse.
#. To create a new guestbook, click the Create Dataset Guestbook button on the rightside of the page. 
#. Name the guestbook, determine the account information that you would like to be required (all account information fields show when someone downloads a file), and then add Custom Questions (can be required or not required). 
#. Hit the Create Dataset Guestbook button once you have finished.

What can you do with a guestbook?
After creating a guestbook, you will notice there are several options for a guestbook and appear in the list of guestbooks. 

- If you want to use a guestbook you have created, you will first need to click the button in the Action column that says Enable. Once a guestbook has been enabled, you can go to the License + Terms for a dataset and select a guestbook for it.

- There are also options to view, copy, edit, or delete a guestbook.

- Once someone has downloaded a file in a dataset where a guestbook has been assigned, an option to download collected data will appear. 


.. _featured-dataverses:

Featured Dataverses
======================================================

Featured Dataverses is a way to display sub dataverses in your dataverse that you want to feature for people to easily see when they visit your dataverse. 

Click on Featured Dataverses and a pop up will appear. Select which sub dataverses you would like to have appear. 

Note: Featured Dataverses can only be used with published dataverses.

Linked Dataverses + Linked Datasets
======================================================


Publish Your Dataverse
=================================================================

Once your dataverse is ready to go public, go to your dataverse page, click on the "Publish" button on the right 
hand side of the page. A pop-up will appear to confirm that you are ready to actually Publish, since once a dataverse
is made public, it can no longer be unpublished.


.. |image1| image:: ./img/Dataverse-Diagram.png
.. |image2| image:: ./img/dvperms1.png
.. |image3| image:: ./img/dv2.png
.. |image4| image:: ./img/dv3.png
.. |image5| image:: ./img/dv4.png
.. |image6| image:: ./img/dv5.png



