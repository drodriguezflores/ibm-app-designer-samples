# The Administrator: Publishing the App for End Users to Consume

In this part of the sample, an administrator takes the app developed by the assembler and makes it available for end users.
___
**Ensure you have the MortgagePA process app imported into Workflow as indicated [here](../README.md).**
___
1. Open BAStudio and ensure the view mode in the user preferences is set to advanced.
2. Go into the details for MortgageApproval and choose the Versions panel.
3. At the end of the version row, click on the options (3 vertical dots) button and then Export.
4. In the dialog, choose .zip then complete the dialog.

![alt text](./images/ExportApp.png "Export App")

5. Open Automation Navigator as an administrator in a browser.
6. Choose Administration, then choose Connections.
7. Select the connection for the app engine, then click Edit.
8. Select the "Connect..." button and enter the credentials for the app engine if necessary.  This will enable the Applications tab.
9. Select the Applications tab.
10. Click the Import button and choose the install zip file that you obtained previously.

![alt text](./images/ImportApp.png "Import App")

11. Now that the app is deployed on the app engine, you can add it to a desktop. Click Desktops and select the desktop that you want to include the app.  Press the Edit button.
12. Select the Layout tab and you should see the app that you just deployed listed in the Displayed features section.  Select the app and save the desktop.

![alt text](./images/AddToDesktop.png "Add to Desktop")

13. Reload the page as instructed and the app should show alongside all other apps.
14. Run the app by filling out the fields.  Use "Joe" for the name for the customer ID lookup to work properly.  If the mortgage amount is less than the yearly income, then the automatic approval path will be traversed.  Clicking Open Account and Exit will launch the process in workflow.  The process contains a user task which you can see in the work dashboard or process portal.
