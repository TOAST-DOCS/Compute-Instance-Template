## Compute > Instance Template > Console User Guide

### Create an instance template
Followings are the items required to prepare an instance template.

<table class="it">
  <tr>
    <th>Category</th>
    <th>Option</th>
    <th>Description</th>
  </tr>
  <tr>
    <td rowspan="2">Template information</td>
    <td>Name</td>
    <td>Instance template name</td>
  </tr>
  <tr>
    <td>Description</td>
    <td>Description on the instance template, up to 255 alphabet characters</td>
  </tr>
  <tr>
    <td rowspan="7">Instance information</td>
    <td>Image</td>
    <td>OS image of the instance to be created</td>
  </tr>
  <tr>
    <td>Availability area</td>
    <td>Area where the instance will be created</td>
  </tr>
  <tr>
    <td>Instance name</td>
    <td>Name of the instance to be created</td>
  </tr>
  <tr>
    <td>Instance Type</td>
    <td>Spec of the instance to be created</td>
  </tr>
  <tr>
    <td>Key pair</td>
    <td>Key to access to the instance to be created</td>
  </tr>  
  <tr>
    <td>Block storage type</td>
    <td>Basic disc type of the instance to be created</td>
  </tr>
  <tr>
    <td>Block storage size(GB)</td>
    <td>Basic disc size of the instance to be created<br>The size is restricted by the spec of the instance</td>
  </tr>
  <tr>
    <td rowspan="3">Network information</td>
    <td>Network</td>
    <td>Network to be connected to the instance to be created<br>When connecting to multiple networks, the first network will be set as the default gateway address</td>
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
    <td>Additional block storage</td>
    <td>Set the name, type, and size of the disc to be assigned additionally to the instance to be created</td>
  </tr>   
  <tr>
    <td>User script</td>
    <td>Script to be executed immediately after booting from the instance to be created</td>
  </tr>
</table>

> [Notes]
> Additional block storage is available after mount processing through user script. See [Block storage guide](/Storage/Block%20Storage/en/overview/#_2) for the mount processing through user script.

<br/>

> [Caution]
> The instance template cannot be modified once created.
