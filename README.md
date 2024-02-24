# Kali-Linux-VM-Set-Up


--- A Quick Step by step guide for Setting up Kali Linux ---

- Download the Kali Linux Iso
    - Visit the offical website of kali Linux (https://www.kali.org/get-kali/#kali-platforms) and download the appropriate ISO Image for your system/Specs. 

- Now, to download/create the Virtual machine: 

  1. Go the offical website at (https://www.virtualbox.org/) and download the latest version of the machine.

  2. Once the Virtual box is finished downloading, open up the Virtualbox and click on the "New" button in the center of the application.
   
      ![image](https://github.com/ImpulseSec/Kali-Linux-VM-Set-Up/assets/160674287/24d81f35-26cf-49ce-b0ef-faf865de302b)

  3. Enter a name for your VM ( Example: Kail linux 2024)

  4. Next, select "linux" as the type and then "Debain - 64 bit" for the version.

  5. Now, Allocate the memory (RAM) according to your system's specifications

  6. click on Create a new virtual hard disk or use an existing one if you have one.

- Configuring the Virtual Machine Settings: 

  1. Begin by selecting your newly created virtual machine and clicking on "Settings." 
  2. Navigate to the "System" tab, where you can adjust the number of CPUs allocated under the "Processor" section for optimal performance. 
  3. Next, enhance display performance by increasing the video memory in the "Display" tab. 
  4. Finally, ensure proper installation by attaching the Kali Linux ISO to the virtual optical drive under the "Storage" tab.

- Installing Kali Linux on the VM

  1. Start the Virtual machine and it will boot from the Kali Linux ISO that you downloaded and imported previously.
  2. Once the machine starts up with a separate window, follow the on-screen prompts to install Kali Linux.
  3. Choose the graphical or text-based installer per your preference. The GUI is preferably the easiest to start with. 
  4. Complete the installation process by setting up the root password and creating a user account for daily use.


Once all the following steps are completed, Kali Linux should be up and running! 

Welcome to the world of Linux! :)



