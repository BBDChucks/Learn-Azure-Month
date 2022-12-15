# Learn Azure in a Month of Lunches (2018)
__By Iain Foulds__     
[Github Example Code](https://github.com/fouldsy/azure-mol-samples)  
[MS Docs for Azure](https://learn.microsoft.com/en-us/azure)  

## Part 1:  Azure Core Services
### Chapter 1: Before you begin

__Installing Azure CLI__  
For MacOS, install using _homebrew_  
```
$ brew update
$ brew install azure-cli
$ az version
```
For other OS see [how to install the Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)

__Understanding the Azure Platform__    
Most of what you create in Azure falls into the IaaS and PaaS areas. The main use cases include VMs and virtual networking (IaaS), or the Azure Web Apps, Functions, and Cosmos DB (PaaS) services.

__Virtualization in Azure__   
Virtualization logically divides physical resources in a server into virtual resources that can be securely accessed by individual workloads. A VM is one of the most common resources in cloud computing. A VM contains a virtual CPU (vCPU), memory (vRAM), storage (vDisk), and network connectivity (vNIC).    
[Explore Azure global infrastructure](https://azure.microsoft.com/en-us/explore/global-infrastructure/)  

__Management__  
There are various management tools available to manage your resources  
* [Azure Portal](http://portal.azure.com)  
* [Azure PowerShell](https://learn.microsoft.com/en-us/powershell/azure/get-started-azureps)  
* [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)
* [Azure Cloud Shell](http://shell.azure.com)
