This repository contains Salesforce / Omnistuido Code and Configuration components for Dynamic Customer Support Case Management System.

1. Get Details of the case about the Customer Issue.
2. Show the basic Resolution Steps according to the CaseType.
3. Fetch Relevant articles from External System as it is Integrated with NewsApi Org.
4. Capture any Follow Up Actions required and create a Task with a date for the same.
5. Show the summary of Case Details and Actions to be taken for the Case.
6. Allow the Agent to confirm the details and submit the case.
7. Send Email to the Customer about intimating the case creation.
8. In the end, agent can use the Open Case Button to redirect himself to the newly created case.

## How Do You Plan to Deploy Your Changes?

To Deploy code to your Salesforce Omnistudio Org, please create a Salesforce / Omnistudio Developer Account and follow below steps as given.

1. Install below items in your Local System from below given URL.
    1. VS Code
    2. SFDX CLI
    3. Salesforce Extensions for VS Code

2. Open VS Code and Select a New Folder, give an appropriate name to the folder.

3. Perform below command in your VS Code Terminal.
    1. git clone 'https://github.com/amrit-github/K2-Use-Case-2-Solution-OmniOrg.git'

4. After clone is completed, press CTRL + SHIFT + P to open Command Pallette and search for SFDX: Authorize an Org.

5. Give name to your org, Select Standard Template and use Production URL (login.salesforce.com) and Login with your credentials and Allow Access to SFDX CLI to your org when prompted.

6. Now Open package.xml in VS Code and right click and select Deploy to Org to bring all changes to yur Personal Developer account. Go to your Org -> Search for Premission Set from SetUp -> Look for 'CredsAccessPermissionSet' assign it to yourself.

7. In the Omniscript Folder, get the JSON, and go to Org -> App Launcher -> Omniscripts -> Import button (at the top right) -> Select the JSON and Import.

8. Make sure you have deployed the package.xml changes first before deploying OmniScirpt JSON file. 

9. Go to SetUp in you Salesforce Org and open the Imported Omniscript -> Activate the version -> How To Launch -> Copy the URL under Lightning section -> Open the copied link in a new Browser tab -> This will open the Case Support Management System in your OmniStudio Org.

10. You are all Set now!
    
# Salesforce DX Project: Next Steps

Now that you’ve created a Salesforce DX project, what’s next? Here are some documentation resources to get you started.

Do you want to deploy a set of changes, or create a self-contained application? Choose a [development model](https://developer.salesforce.com/tools/vscode/en/user-guide/development-models).

## Configure Your Salesforce DX Project

The `sfdx-project.json` file contains useful configuration information for your project. See [Salesforce DX Project Configuration](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_ws_config.htm) in the _Salesforce DX Developer Guide_ for details about this file.

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
