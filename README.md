# Futureintern_CYS_01
TASK 1

Step 1: Download Kali Linux ISO
1.Visit the Kali Linux website:
Kali Linux Downloads.
2.Select the appropriate version:
1.Installer ISO: Ideal for VirtualBox installations.
2.64-bit (x64): Recommended unless you have older hardware.
3.Click on the download link to start downloading the ISO file.

Step 2: Download and Install VirtualBox
1.Visit the VirtualBox website:
VirtualBox Downloads.
2.Download and install the version compatible with your operating system (Windows, macOS, or Linux).

Step 3: Create a Virtual Machine
1.Open VirtualBox.
2.Click on New to create a new virtual machine.
3.Fill in the following details:
1.Name: Give your virtual machine a name (e.g., Kali Linux).
2.Type: Select Linux.
3.Version: Choose Debian (64-bit).
4.Click Next.

Step 4: Configure Virtual Machine Settings
1.Allocate Memory (RAM):
1.Minimum: 2GB (Recommended: 4GB or more for better performance).
2.Create a Virtual Hard Disk:
1.Select Create a virtual hard disk now.
2.Choose VDI (VirtualBox Disk Image).
3.Select Dynamically allocated.
4.Allocate at least 20GB of storage.

Step 5: Attach Kali Linux ISO
1.Select your newly created virtual machine and click on Settings.
2.Go to Storage.
3.Under Controller: IDE, click the empty disk icon.
4.On the right, click Choose a disk file and select the Kali Linux ISO you downloaded.
5.Click OK.

Step 6: Start the Virtual Machine
1.Select your virtual machine and click Start.
2.The Kali Linux installer will boot.
3.Choose Graphical Install or Install.

Step 7: Install Kali Linux in VirtualBox
1.Follow the installation process:
1.Select your language, location, and keyboard layout.
2.Configure the network (use a wired or NAT connection).
3.Set up a root password (or a regular user in newer versions).
2.Partition the Disk:
1.Use Guided - use entire disk for simplicity.
3.Install GRUB Bootloader:
1.Install GRUB when prompted.

Step 8: Finalize and Start Using Kali
1.Once installation is complete, restart the virtual machine.
2.Remove the ISO:
1.Go to Settings > Storage, and remove the ISO file from the virtual optical drive.
3.Start Kali Linux and log in using the credentials you set.

Relevant Screen shot:

Kali Linux installation:



Virtual Box installation



















Steps to Perform an XSS Test:
1. Identify Potential Vulnerabilities
Look for input fields or URL parameters on the website where user input is reflected in the page output. Examples:
oSearch bars
oComment boxes
oLogin forms
oURL query strings
2. Inject a Basic Payload
Use a simple JavaScript alert payload to test if the input field is vulnerable:
This  is the JavaScript that I pasted in the search box of the testphp.vulnweb.com site and it shows that the website is vulnerable to the XSS attacks and shows me the pop-up 

<script>alert('The website is hacked!');</script>










