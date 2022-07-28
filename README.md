# Intersight Cloud Orchestrator - Intersight Kubernetes Service

## Use Case
These tasks and worfklows allow you to configure and deploy Kubernetes clusters via the Intersight Kubernetes Service.

## Overview
Right now, this repository contains the following tasks and workflows:

### Tasks
<table>
  <tr>
    <th>Object</th>
    <th>Operation</th>
    <th>Maintainer</th>
    <th>Status</th>
    <th>Link</th>
  </tr>
  
  <!-- Add-Ons Policy -->
  <tr>
    <td rowspan="2">Add-Ons Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/CreateAdd-OnsPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- Cluster Profile -->
  <tr>
    <td rowspan="4">Cluster Profile</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/CreateClusterProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Deploy</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/DeployClusterProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Undeploy</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/UndeployClusterProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/DeleteClusterProfile.json">Link</a></td>
  </tr>
  
  <!-- Container Runtime Policy -->
  <tr>
    <td rowspan="2">Container Runtime Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/CreateContainerRuntimePolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- Kubernetes Version Policy -->
  <tr>
    <td rowspan="2">Kubernetes Version Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/CreateKubernetesVersionPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- Network CIDR Policy -->
  <tr>
    <td rowspan="2">Network CIDR Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/CreateNetworkCIDRPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- NodeGroup Profiles -->
  <tr>
    <td rowspan="3">NodeGroup Profile</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/CreateNodeGroupProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Scale</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/ScaleNodeGroupProfile.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- Node OS Configuration Policy -->
  <tr>
    <td rowspan="2">Node OS Configuration Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/CreateNodeOSConfigurationPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- Trusted Certificate Authorities Policy -->
  <tr>
    <td rowspan="2">Trusted Certificate Authorities Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/CreateTrustedCertificateAuthoritiesPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- Virtual Machine Infra Config Policy -->
  <tr>
    <td rowspan="2">Virtual Machine Infra Config Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/CreateVirtualMachineInfraConfigPolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
  
  <!-- Virtual Machine Instance Type Policy -->
  <tr>
    <td rowspan="2">Virtual Machine Instance Type Policy</td>
    <td>Create</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/CreateVirtualMachineInstanceTypePolicy.json">Link</a></td>
  </tr>
  <tr>
    <td>Delete</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./tasks/DeleteManagedObject.json">Link*</a></td>
  </tr>
</table>
* These Delete operations use the generic "Delete Managed Object" task for Intersight

### Workflows
<table>
  <tr>
    <th>Action</th>
    <th>Maintainer</th>
    <th>Status</th>
    <th>Link</th>
  </tr>
  
  <tr>
    <td>Create and deploy a new cluster</td>
    <td><a href="https://github.com/3191110276">Michael Maurer</a></td>
    <td>:white_check_mark: Implemented</td>
    <td><a href="./workflows/CreateanddeployanewCluster.json">Link</a></td>
  </tr>
</table>

## Prerequisites
You will need to have Intersight Kubernetes Service enabled and licensed. All prerequisites for the Kubernetes Service will need to be fulfilled to use the automation.


## Claimed Targets
None


## Notes
Right now the workflow only works for ESXi, not Intersight Workload Engine (IWE).
