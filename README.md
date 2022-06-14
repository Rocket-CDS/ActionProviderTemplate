# ActionProviderTemplate

This Visual Studio template can be used to quickly create an ActionProvider.  

## Action Provider
An action provider is designed to do a single action on the system installation, usually to update records or fix problems.  
The action provider assembly should inherit the "ActionProvider" class from the RocketPortal project.



**Step 1**  - Change the project name "ActionProviderTemplate" to your new project name.  Names MUST be unique for each installation.  
**Step 2**  - Change the class name "ActionProviderTemplate" to your new ActionProvider Class name.  
**Step 3**  - Add you code to the DoAction(string actionData) method in the ActionProvider class.  

### Running

The assembly that will be executed should be installed into the bin folder and then the correct assembly, namespace, class and extra data can be added the the AdminCDS "Global Settings" UI.  

