# Sharepoint-info
Toxikon Sharepoint info-Maintenence Request and others
http://maintreq:22907/sites/requestcenter/SitePages/My%20Requests.aspx

The Toxikon Request Sharepoint site has been developed to replace the Lotus Notes system that we were/are using.  
To create a new sharepoint requester on this site, follow the below steps:

1.  Remote Desktop into the maintreq server. (I would recommend having a browser also open to the sharepoint site on your own machine to live test)
2.  Open Sharepoint Designer 2013, open site, and click on the request center website.
3.  Create a custom list.  For reference for the column fields to include, you can switch back and forth from Maintence Request (or any other list) to see what fields and what types they are. 
4.  Create user groups for any workflow logic that you will need.
5.  Open your newly created custom list.  On the dashboard page, in the Workflows section, you can click on new to create a new workflow.
6.  Again, using Maintenance Requester for reference, add the required steps to the workflow.  Most workflows on the site run in an impersonation step.  For any major steps like starting approval processes or collecting data from a group, find the boilerplate in the actions tab in the ribbon. 7.  Once you're on the workflow dashboard page, under start options, have all first first-tier boxes checked (so the workflow will start when an item is created or changed). 
8.  Return back to the list dashboard.  You can create custom forms (so that not all information is available for the user to create and edit) in the forms section.  To do this, create a new form of the correct type, delete any fields that you want to be automatically generated and edited, and set a default value for the value in the edit list columns view.  You can do the same for the history view (use a query tag in the view template).
9.  Under general settings, click "Display this list on the Quick Launch" to have the requester show up on the nav bar on the left of the site. 