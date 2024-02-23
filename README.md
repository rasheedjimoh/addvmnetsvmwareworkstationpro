# Enhancing Virtual Machine Connectivity: Adding Network Adapter in VMware Workstation Pro

<img width="602" alt="vm-ware-add-more-vmnet - gh" src="https://github.com/rasheedjimoh/addvmnetsvmwareworkstationpro/assets/157264080/f4c53c26-1613-49b2-9136-e16e1d6eeff4">


## Process/Procedure
To add a network adapter to your VMware Workstation Pro using the Virtual Network Editor, follow these steps:

1. **Open Virtual Network Editor:**
   - Launch VMware Workstation Pro.
   - Navigate to the "Edit" menu at the top.
   - Select "Virtual Network Editor" from the dropdown menu. This will open the Virtual Network Editor window.

2. **Modify Virtual Network Settings:**
   - In the Virtual Network Editor window, you'll see a list of available virtual networks.
   - Click on the "Add Network" button to add a new network adapter.
   - Choose the type of network adapter you want to add (e.g., VMnet2, VMnet3, etc.). Each VMnet corresponds to a virtual network adapter.
   - Once you've selected the network adapter type, click on the "OK" or "Apply" button to save the changes.

3. **Configure Network Adapter in VMware Workstation:**
   - Close the Virtual Network Editor window.
   - In VMware Workstation Pro, select the virtual machine you want to add the network adapter to from the library.
   - Power off the virtual machine if it's currently running.

4. **Add Network Adapter to Virtual Machine:**
   - With the virtual machine selected, go to the "Edit virtual machine settings" option. You can find this in the toolbar or right-click menu.
   - In the Virtual Machine Settings window, click on the "Add" button.
   - Choose "Network Adapter" from the list of hardware types and click "Next".
   - Select the virtual network adapter you added earlier (e.g., VMnet2, VMnet3) from the dropdown menu.
   - Click "Finish" to add the network adapter to the virtual machine.

<img width="594" alt="image" src="https://github.com/rasheedjimoh/addvmnetsvmwareworkstationpro/assets/157264080/149d0c57-42a4-43fa-9c0b-e1ecf8c2a78f">


5. **Configure Network Settings in Guest OS:**
   - Start the virtual machine.
   - Once the guest operating system is booted up, configure the network settings as needed within the guest OS. This typically involves assigning an IP address, subnet mask, gateway, DNS servers, etc., depending on your network configuration.

6. **Test Connectivity:**
   - After configuring the network settings, test the connectivity to ensure that the virtual machine can communicate over the new network adapter.
