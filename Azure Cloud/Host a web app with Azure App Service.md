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

- Azure Repos helps you to define your own build and release process. A full process that compiles your source code, runs the tests, builds a release, and finally deploys the release into your web app every time you commit the code. All that happens implicitly, without any need for you to intervene.

### Integrated Visual Studio publishing and FTP publishing
In addition to being able to set up continuous integration/deployment for your web app, you can always benefit from the tight integration with Visual Studio to publish your web app to Azure via Web Deploy technology. App Service also supports FTP-based publishing for more traditional workflows.

### Built-in auto scale support
The ability to scale up/down or scale out is baked into the web app. Depending on the web app's usage, you can scale your app up/down by increasing/decreasing the resources of the underlying machine that's hosting your web app. Resources can be the number of cores or the amount of RAM available. On the other hand, you can scale out your app by increasing the number of machine instances that are running your web app.

## Creating a web app

- Visit Azure portal and create a **Web App** resource. It allocates a set of hosting resources in App Service. You can use these resources to create any web-based app. Azure supports whether its ASP.NET Core, Node.js, Java, Python and so on.

To create a Web App, you need the following fields:

- **Resource Group** - A Valid resource group.
- **Name** - Name of the web app. (Must be unique)
- **Publish** - You can deploy your application to App Service as **code** or as a ready-to-run Docker **Container**. Selecting **Container** activates the wizard's Container tab, where you provide information about the Docker registry from which App Service retrieves your image.
- **Runtime stack** - If you choose to deploy your application as code, App Service needs to know what runtime your application uses (examples include Node.js, Python, Java, and .NET). If you deploy your application as a container, you don't need to choose a runtime stack, because your image includes it.
- **Operating system** - 


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTA3Nzk1MTg4MSwtNTgwNzQ3MDAwLDE1Nz
gwNDAwNzAsLTI5OTg1MzYyMywzNTY4MDkyODUsLTE2Nzk2Nzky
ODFdfQ==
-->