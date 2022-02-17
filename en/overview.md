## Compute > Instance Template > Overview

The Instance Template is a service that predefines and stores frequently used instance component information. You can use a predefined instance template to create an instance with the same specification easily, or use it to create a scaling group for using Autoscale.

## Instance Template Components
The instance template predefines the following components that compose the instance.

* **Image**: A virtual disk image containing the instance's OS
* **Availability zone**: Physical location where the instance is to be created
* **Flavor**: Performance of the virtual hardware of the instance
* **Key pair**: Key used as the means to access to the instance
* **Block storage**: Type and capacity of the default disk to be attached to the instance
* **Network**: Virtual network to be connected to the instance
* **Floating IP**: Whether to use a floating IP
* **Security group**: Network security setting of the instance
* **Additional block storage**: Type and capacity of the disk to be additionally attached to the instance
* **User script**: Script to be automatically executed during the initial booting after the instance is created

> [Notes]
> The role of the instance template is simply to store the component information.
> The instance is not automatically created by simply making an instance template.
