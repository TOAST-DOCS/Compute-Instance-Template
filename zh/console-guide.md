<a id="compute-instance-template-console-user-guide"></a>
## Compute > Instance Template > Console User Guide

<a id="create-an-instance-template"></a>
### Create an Instance Template
The following are the items required to prepare an instance template.

<table class="it">
  <tr>
    <th>Category</th>
    <th>Item</th>
    <th>Description</th>
  </tr>
  <tr>
    <td rowspan="2">Template information</td>
    <td>Name</td>
    <td>Instance template name</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Description of the instance template, up to 255 alphabet characters</td>
  </tr>
  <tr>
    <td rowspan="2">OS Settings</td>
    <td>Newly create and configure</td>
    <td>Create a root block storage by using an image</td>
  </tr>
  <tr>
    <td>Specify the existing resource</td>
    <td>Use the snapshot previously created</td>
  </tr>
  <tr>
    <td rowspan="4">Root Block Storage</td>
    <td>Original resource</td>
    <td>Select the original snapshot to generate a root block storage<br>Block storage type and availability zone cannot be changed, and block storage size can only be scaled out</td>
  </tr>
  <tr>
    <td>Block Storage Type</td>
    <td>Default disk type of instances to be created</td>
  </tr>
  <tr>
    <td>Block Storage Size (GB)</td>
    <td>Default disk size of instances to be created<br>Size is limited by the instance's specifications</td>
  </tr>
  <tr>
    <td>Symmetric Key ID</td>
    <td>Symmetric key ID of the Secure Key Manager service to be used to create encrypted block storage</td>
  </tr>
  <tr>
    <td rowspan="5">Instance Information</td>
    <td>Image</td>
    <td>OS image of the instance to be created</td>
  </tr>
  <tr>
    <td>Availability Zone</td>
    <td>Area where the instance will be created</td>
  </tr>
  <tr>
    <td>Instance Name</td>
    <td>Name of the instance to be created</td>
  </tr>
  <tr>
    <td>Flavor</td>
    <td>Specification of the instance to be created</td>
  </tr>
  <tr>
    <td>Key Pair</td>
    <td>Key to access the instance to be created</td>
  </tr>
  <tr>
    <td rowspan="3">Network information</td>
    <td>Network</td>
    <td>Network to connect to the instance to be created<br>If multiple networks are connected, the first network will be set as the default gateway address</td>
  </tr>
  <tr>
    <td>Floating IP</td>
    <td>Whether to assign a floating IP to the instance to be created</td>
  </tr>
  <tr>
    <td>Security Group</td>
    <td>Security rule of the instance to be created</td>
  </tr>
  <tr>
    <td rowspan="2">Additional information</td>
    <td>Additional Block Storage</td>
    <td>Set the name, type, and size of the disk to be additionally assigned to the instance to be created</td>
  </tr>   
  <tr>
    <td>User Script</td>
    <td>Script to be executed immediately after booting by the instance to be created</td>
  </tr>
</table>

> [Notes]
> The additional block storage becomes available after mount processing through a user script. See [block storage guide](/Storage/Block%20Storage/en/overview/#use-empty-block-storage) for the mount processing through user script.

<br/>

> [Caution]
> The instance template cannot be modified once created.

<a id="change-instance-template-owner"></a>
### Change Instance Template Owner
When you click an owner to change, the instance template owned by the owner is displayed. Select an instance template where you want to change the owner to yourself.
After the change, the instance template can be managed by the key pair you selected when changing the owner.