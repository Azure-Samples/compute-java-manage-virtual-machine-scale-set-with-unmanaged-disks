---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Compute
  platforms: java
---

# Getting Started with Compute - Manage Virtual Machine Scale Set With Unmanaged Disks - in Java #


  Azure Compute sample for managing virtual machine scale sets with un-managed disks -
   - Create a virtual machine scale set behind an Internet facing load balancer
   - Install Apache Web servers in virtual machines in the virtual machine scale set
   - List the network interfaces associated with the virtual machine scale set
   - List scale set virtual machine instances and SSH collection string
   - Stop a virtual machine scale set
   - Start a virtual machine scale set
   - Update a virtual machine scale set
     - Double the no. of virtual machines
   - Restart a virtual machine scale set
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/compute-java-manage-virtual-machine-scale-set-with-unmanaged-disks.git

    cd compute-java-manage-virtual-machine-scale-set-with-unmanaged-disks

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.