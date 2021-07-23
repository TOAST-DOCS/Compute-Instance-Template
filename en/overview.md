## Compute > Instance Template > Overview

The Instance Template is a service that pre-defines and stores frequently used instance component information. User can use a predefined instance template to easily create an instance with the same specification, or use it to create a scaling group to use Autoscale.

## Instance Template Component
The instance template pre-defines the following components constituting the instance.

* **Image**: A virtual disk image containing the instance's OS
* **Availability area**: Physical location where the instance to be created
* **Instance type**: Virtual hardware performance of the instance
* **Key pair**: Key used as the means to access to the instance
* **Block storage**: Type and capacity of the default disc to be connected to the instance
* **Network**: Virtual network to be connected to the instance
* **Floating IP**: Whether to use a floating IP
* **Security group**: Set the instance network security
* **Additional block storage**: Type and capacity of the disc to be additionally connected to the instance
* **Reservation script**: Script to be automatically executed during the initial booting after Create Instance

> [Notes]
> The role of the instance template is simply to store the component information.
> The instance is not automatically created by simply making an instance template.
