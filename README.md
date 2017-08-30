# AzureCapturCereator
Description
-----------
Script to Create a capture of your Azure VM's.

If you're familiar to AWS and new to Azure this is similar to creating a AMI.

Although Captures are limited to the resource they belong to.

Prerequisuites
-----------
Azure CLI installed locally

Installation
-----------
Download or clone the repository

Make the script executable <code>sudo chmod +x createCapture.sh</code>

Usage
-----------
Before running the script you will need to deprovision the VM you wish to Capture
 - Log in to the VM through SSH
 - Run <code>sudo waagent -deprovision+user</code>
 
Once completed type <code>exit</code>

For more information see https://docs.microsoft.com/en-us/azure/virtual-machines/linux/capture-image

Return to terminal on local machine and run the script <code>./createCapture.sh</code>

Licence
-----------
MIT
 
