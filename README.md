# System-Virtualization-Project

## Objective

This System Virtualization project aimed to test my knowledge in using VMware. This was for a school final, however I see the potential in being able to work your way around this specific vendor. In this lab I will list all the instructions given to me and drop the image of the completed task below.

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

2. Setup and Configure VMware ESXi-YourName Host
- Add host to vCenter inventory
- Take screenshot (paste below)

3. Create a Virtual Machine on an ESXi host

- Name: YourName-VM
- OS: Linux - Red Hat Fedora
- CPU: leave defaults
- RAM: 1 GB
- Hard Drive: 8 GB (thin provisioned)
- Take screenshot from VM summary screen (paste below).

4. Create a new folder in the Training datacenter called Final

- Clone you’re YourName-VM to become a template
- Name it YourName-Temp
- Take screenshot (paste below)

5. Add a Virtual Switch and iSCSI storage device to an ESXi host

- Take screenshot (paste below).



6. Create a VMFS Datastore called YourName-DS

- Take screenshot (paste below)



7. Create a resource pool named YourName-Final

- Take screenshot (paste below).



8. Take snapshots of your YourName-VM virtual machine

- Take screenshot of your snapshot (paste below).


9. Create a new user account called YourName with Virtual Machine Creator permissions. 
Take screenshot (paste below).

10. Take a screenshot of the CPU utilization on an ESXi host (paste below).




