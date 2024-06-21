# System-Virtualization-Project

## Objective

This System Virtualization project is aimed to test my knowledge in using VMware (a service used to manage and administrate virtualization recources). This was for a school final, however I see the potential in being able to work your way around this specific vendor. In this lab I will list all the instructions given to me and drop the image of the completed task below.

### Skills Learned

- Advanced understanding of virtualization, administration and configuration
- Proficiency in effectively using VMware administration tools
    - vSphere Client, vServer and ESXi

### Tools Used

- vSphere Client
- vServer
- ESXi

## Steps

1. Setup and Configure VMware vCenter Server Appliance on an ESXi host (steps only, no depoloyment)

- Name is vCenter-YourName
- Take screenshot of setup summary page, the page before clicking finish (paste below)

![IMG_0477](https://github.com/Matike-Beseke/System-Virtualization-Project/assets/172703140/84dc9c5f-db65-42ec-8371-433c7b2e21a7)

2. Setup and Configure VMware ESXi-YourName Host
- Add host to vCenter inventory
- Take screenshot (paste below)

![IMG_0478](https://github.com/Matike-Beseke/System-Virtualization-Project/assets/172703140/9f5edcd4-8722-4f10-9056-84e8687a50c6)

3. Create a Virtual Machine on an ESXi host

- Name: YourName-VM
- OS: Linux - Red Hat Fedora
- CPU: leave defaults
- RAM: 1 GB
- Hard Drive: 8 GB (thin provisioned)
- Take screenshot from VM summary screen (paste below).

![IMG_0479](https://github.com/Matike-Beseke/System-Virtualization-Project/assets/172703140/2578f410-e112-45c4-a18c-4c64540e524d)

4. Create a new folder in the Training datacenter called Final

- Clone you’re YourName-VM to become a template
- Name it YourName-Temp
- Take screenshot (paste below)

![IMG_0480](https://github.com/Matike-Beseke/System-Virtualization-Project/assets/172703140/f50708c3-5d8e-4212-a8b3-d5f19181d53c)

5. Add a Virtual Switch and iSCSI storage device to an ESXi host

- Take screenshot (paste below).

![IMG_0481](https://github.com/Matike-Beseke/System-Virtualization-Project/assets/172703140/55013f5e-4fcc-42d8-bc5b-daebc2ff8101)

6. Create a VMFS Datastore called YourName-DS

- Take screenshot (paste below)

![IMG_0482](https://github.com/Matike-Beseke/System-Virtualization-Project/assets/172703140/81e22bae-11dc-404b-ae73-d649b3b8dfca)

7. Create a resource pool named YourName-Final

- Take screenshot (paste below).

![IMG_0483](https://github.com/Matike-Beseke/System-Virtualization-Project/assets/172703140/c2dc807f-c7d4-4ef4-8ffa-71d1a4cb080d)


8. Take snapshots of your YourName-VM virtual machine

- Take screenshot of your snapshot (paste below).

![IMG_0484](https://github.com/Matike-Beseke/System-Virtualization-Project/assets/172703140/44ebbb57-be21-454e-95ed-cb9ea6eb0028)

9. Take a screenshot of the CPU utilization on an ESXi host (paste below).

![IMG_0488](https://github.com/Matike-Beseke/System-Virtualization-Project/assets/172703140/8cf9441f-dee8-4d9c-9d06-223c8d4a48fd)


