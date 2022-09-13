# Windows Credential Manager
  
Obtains credentials from the Windows credential manager. 

*Read this in other languages: [English](Manual_WindowsCredentialManager.md), [Español](Manual_WindowsCredentialManager.es.md), [Portugués](Manual_WindowsCredentialManager.pr.md)*
  
![banner](imgs/Banner_WindowsCredentialManager.png)
## How to install this module
  
__Download__ and __install__ the content in 'modules' folder in Rocketbot path  


## How to use this module
1. Type in the Windows search engine "Credential Manager" and open it.
2. Click on "Windows Credentials".
3. In the Generic Credentials section click on "Add a generic credential".
4. You will have to fill in the information with a network address, username and password (these can be any values you want).
5. In the Rocketbot command you must type the name of the network address in order to obtain its values.


## Description of the commands

### Get Credential
  
Get credential from Windows Credential Manager
|Parameters|Description|example|
| --- | --- | --- |
|Internet or network address|Internet or network address of the generic credential|rocketbot.com|
|Assign user result to a Variable|Assigns the credential user to a variable|Variable 1|
|Assign password result to a Variable|Assigns the credential password to a variable|Variable 2|
