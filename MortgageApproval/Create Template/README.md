# The Provider: Creating an action and a template for the assembler to use.

In this part of the sample, the provider (a technical user) creates a business-level action for the assembler to use in their app. Ths action is authored in a toolkit, allowing them to be reused in the future. The provider also creates a template as a starting point for app authoring.  The template specifies the starting point for the user interface of the app and which toolkits the app should reference.

1. Open BAStudio and ensure the view mode in the user preferences is set to advanced.

![alt text](./images/PrefMenu.png "Preferences Menu")

![alt text](./images/PrefAdvanced.png "Advanced Mode")

2. In the Toolkits panel, import "CreditDeptTK - v9.twx".  This twx file has the Customer business object and an associated view. It also contains a common header used by the fictitious credit department. 

3. Return to Studio and create a template called MortgageAppTemplate.

![alt text](./images/CreateTemplate.png "Create Template")

4. After the editor is opened, delete the Default Navigation Bar. On the Page Dialog, open the Default Navigation Bar.

![alt text](./images/PageDefaultNavigationBar.png "Page Default Navigation Bar")

5. Delete this page. Go back to the Starting Page, and delete the referenced common area as this is now removed.

![alt text](./images/DeleteReferencedArea.png "Delete ReferencedArea")

6. Add CreditDeptTK as a toolkit dependencies. This can be done by clicking on the briefcase logo on the left library panel, and adding a Toolkit.

7. In the App, add CreditDeptTempl to the first page by dragging the view from the palette into the layout. Press the finish editing button.

![alt text](./images/Template.png "Mortgage App Template")

8. Create a snapshot of the template.
