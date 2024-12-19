## Objectives
- Use Azure Portal to create an Azure App Service web app.
- Use developer tools to create the code for a starter web application.
- Deploy your code to App Service.

## Why Azure Portal
- The first step in hosting your web app is to create a web app(An Azure App Service) inside your Azure Account.

You can create a web app in the following ways:

- Through Azure Portal.
- Through Azure CLI.
- Through a script or IDE like VS Code.

The Azure Portal is a graphical interface helps to learn easier.

## Azure App Service

It is a fully managed web app hosting platform. It allows you to focus on design and building the web app while it takes care of the infrastructure to run and scale your applications.

### Deployment slots
Deployment slots are live apps with their own hostnames. For Example, you can create a staging deployment slot to push your code and run tests on Azure. Once you're satisfied with your code, you can easily swap the deployment slot to the production slot.

### Continuous integration/deployment support
Azure provides CI/CD support through **Azure Repos, GitHub, Bitbucket, or a local Git repository** on your deployment machine. It automatically syncs the code and any future changes to the code. 

- Azure Repos helps you to define your own build and release processes.

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTU3NjUyOTc5MiwxNTc4MDQwMDcwLC0yOT
k4NTM2MjMsMzU2ODA5Mjg1LC0xNjc5Njc5MjgxXX0=
-->