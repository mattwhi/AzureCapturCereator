# AzureCapturCereator
Description
-----------
Script to Create a capture of your Azure VM's

Prerequisuites
-----------
Azure CLI installed locally

Installation
-----------
Download or clone the repository
Make the script executable <code>sudo chmod +x createCapture.sh</code>

Usage
-----------
Before running the script you will need to deprovision the VM you wish to cancel
 - Log in to the VM through SSH
 - Run <code>sudo waagent -deprovision+user</code>
Once completed type <code>exit</code>

Return to terminal on local machine and run the script <code>./createCapture.sh</code>

Licence
-----------
MIT
 
