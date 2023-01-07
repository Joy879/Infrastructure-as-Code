### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the  code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:


#### final-project-starter.yml
A YAML guiding template for building the cloud infrastructure, as required for the project. 


#### network.yml
Setting up the network cloud formation for Udagram

#### servers.yml
Sets up the server cloudformation for Udagramservers

#### network-parameters.json
A file that increases the generic nature of YAML code.  For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "Udagram". 


#### server-parameters.json
A file for increasing the generic nature of the YAML code. For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "Udagram". 

In YAML code, the `${EnvironmentName}` would be substituted with `Udagram` accordingly.
