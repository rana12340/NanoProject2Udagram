## NanaProject2Udagram
All code available at 
GIT LOCATION: https://github.com/rana12340/NanoProject2Udagram

## You'll first develop a diagram that you can present as part of your portfolio and as a visual aid to understand the CloudFormation script.
Udagram_Infra_Setup.jpeg- Image of VPC setup
https://github.com/rana12340/NanoProject2Udagram/blob/master/Udagram_Infra_Setup.jpeg

## The second part is to interpret the instructions as well as your own diagram and create a matching CloudFormation script.

- Network.yaml - CloudFormation network infrastructure stack description.
- network-parameters.json - Parameters file for the network infrastructure stack
- services.yaml - CloudFormation services infrastructure stack description
- services-parameters.json - Parameters file for the services infrastructure stack
- create.bat - Batch(using Windows 10) script for Stack's creation


## Script Execution
Step 1) Create network infrastructure stack.
.\create.bat UdagramCloudInfra Network.yaml network-parameters.json

Step 2) Create Services Infra
.\create.bat Udagramservers services.yaml services-parameters.json

## Output
Services stack gives final website URL with Udagram dummy page.

## FinalOutcome Snap
WebsiteSnap.jpg
