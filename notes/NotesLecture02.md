# What is Virtualization?
* Virtualization is the replication of hardware to manage a virtual operating system in your physical machine
* Can be sued to test applications before installing it on your host machine
* Inexpensive for the fact that you don't need to purchase any physical software

# Installing Ubuntu in a virtual machine
* Prepare the virtual machine by naming the machine using it's intended purpose and operating system to organize it and also place the machine in a folder
![image1](../imgs/vmname.png)
* The virtual machine requires a minimum of 2 GB of RAM if there is 8 GB you have 8 GB of RAM you can add 4 RAM to your virtual machine. **Do not give your virtual machine more than half your RAM!**
![image2](../imgs/memorysize.png)
* Create a virtual hard disk so you can create a disk with any size you specify
![image3](../imgs/createhd.png)
* Use the VDI option for the Hard Disk file type
![image4](../imgs/createvdi.png)
* Choose Dynamically Allocated, this will grow until it reaches the max capacity of the disk that was specified
![image5](../imgs/dynamic.png)
* Make the virtual disk 50 GB
![image6](../imgs/filesize.png)
* Click on the virtual machine settings and add the virtual machine details such as username, host name, and password
![image7](../imgs/description.png)
* In system section, under motherboard, disable floppy and put it as the last boot option
![image8](../imgs/floppy.png)
* In display udner screen, Set video memory to 128 MB
* Enable 3D Acceleration
![image9](../imgs/videomemory.png)
* In storage add the Ubuntu ISO in the IDE Controller
![image10](../imgs/IDE.png)
* In audio disable audio
![image11](../imgs/audio.png)