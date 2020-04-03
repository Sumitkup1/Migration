# Migration

As part of migrating workloads to Azure you may need to move some Windows 2003 server for legacy applications /or you may decide to move windows 2003 server to Azure first, then modernise application using Azure PaaS service. While windows server 2003 is out of support however you can still move Windows Server 2003 VMs to Azure. Please review support guidelines available on https://support.microsoft.com/en-us/help/3206074/running-windows-server-2003-on-microsoft-azure
You may encounter below issue with Windows 2003 server in Azure after migration from VMware Source.

# Issue description – 

## Network connectivity doesn’t work with Windows 2003 VMs in Azure

In some cases, you may observe network connectivity issue with Windows Server 2003 virtual machine in Azure after migration from on-premises VMWare infrastructure.

## Symptoms – 
1.	You are not able to ping, RDP or telnet on any port to the migrated virtual machine within /or across subnet. 
2.	You will see ‘Welcome to Windows’ screen in the ‘Boot diagnostics’ feature in Azure platform. 

Refer to the attached document to resolve this issue in Azure.
