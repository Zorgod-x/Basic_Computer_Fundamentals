
### Very Basic Computer Fundamentals
* **Basic BIOS Configurations**
  * **Boot Sequence :**<br>
  The boot sequence determines the order in which the computer checks for and boots from different storage devices (e.g., hard drive, USB drive, CD/DVD drive).
  * **Enabling / Disabling Devices :** <br/>
    <tab>BIOS settings allow users to enable or disable various hardware components, such as USB ports, integrated audio, onboard graphics, or network adapters.
  * **Changing Date / Time :** <br/>
  BIOS includes a real-time clock (RTC) that keeps track of the system's date and time. Users can set or adjust the date and time in BIOS to ensure accurate timestamps for files and system logs.
    * **CMOS Batteries :**<br/>
    BIOS settings are stored in CMOS (Complementary Metal-Oxide-Semiconductor) memory, which requires a small battery to maintain these settings even when the computer is powered off.
  * **CPU Clockspeeds :**<br/>
  BIOS allows users to configure CPU clockspeed settings, including the base clock frequency and the multiplier. Overclocking enthusiasts often use these settings to increase CPU performance.
  * **BIOS Firmware Upgrades :**<br/>
  BIOS firmware upgrades, often referred to as BIOS updates or flashing the BIOS, involve updating the firmware on the motherboard to add new features, improve compatibility, or fix security vulnerabilities. This process should be done with caution.
  * **Enabling Virtualization Support :**<br/>
  Some CPUs support hardware-assisted virtualization, which is crucial for running virtual machines efficiently. In BIOS, users can enable or disable virtualization technology (e.g., Intel VT-x or AMD-V) to enhance virtualization performance.
  * **Secure Boot _(Basic Understanding)_ :**<br/>
  Secure Boot is a security feature that prevents the loading of unauthorized or malicious software during the boot process. It verifies the digital signatures of bootloader files to ensure they haven't been tampered with. Users can typically enable or disable Secure Boot in BIOS.
* **Hard Drive Basics**
  * **Magnetic HDDs :**
  * **SSDs :**
  * **eMMC :**
  * **Partitioning :**
    * **FAT32 :**
    * **NTFS :**
    * **ext2, ext3, ext4 :**
  * **MBR _(Legacy)_ :**
  * **EFI / UEFI :**
* **RAM**
  * **DDR1, DDR2, DDR3, DDR4:**
  * **Memory Speeds:**
  * **Memory Addressing:**
* **CPUs**
  * **Intel:**
    * **i3, i5, i7, i9:**
  * **AMD:**
    * **Ryzen 3, Ryzen 5, Ryzen 7, Ryzen 9:**
  * **32bit CPUs:**
  * **64bit CPUs:**
  * **MultiThreading vs. MultiProcessing:**
* **GPUs**
  * **Integrated vs. Discrete GPUs**
  * **Ray Tracing:**
  * **GPU Memory:**
  * **GPU Bandwidth:**
* **Caching**
  * **Web Caching:**
  * **Data Caching:**
  * **Application/Output Caching:**
  * **Distributed Caching:**
* **Common File Exstentions**
  * **Executables**
    * **.exe:**
    * **.o:**
    * **.sh:**
  * **Library files*
    * **.dll:**
    * **.so:**
    * **.lib:**
  * **Web files**
    * **.html:**
    * **.php:**
    * **.css:**
    * **.js:**
  * **Image files**
    * **.jpg:**
    * **.svg:**
    * **.png:**
  * **Document files**
    * **.doc:**
    * **.txt:**
    * **.pdf:**
  * **Code files**
    * **.c:**
    * **.cpp:**
    * **.py:**
  * **Key files**
    * **.pub:**
    * **.pem:**
    * **.der:**
* **Encoding**
  * Base64
  * ASCII
  * UTF-8
* **RAIDs**
  * RAID 0
  * RAID 1
  * RAID 5
  * RAID 6
  * RAID 10


  Caching:

Caching is a technique used in computing to store and reuse data or resources to speed up access and reduce the load on the original data source. There are various types of caching:

Web Caching:

Web caching involves storing web content (HTML pages, images, stylesheets, etc.) at intermediate points, like web proxies or Content Delivery Networks (CDNs). Cached content can be quickly delivered to users, reducing the load on the origin server and improving website performance.
Data Caching:

Data caching is used to store frequently accessed data in a faster, more easily retrievable location, such as RAM. This speeds up data retrieval and reduces the need to access the original data source, which may be slower.
Application/Output Caching:

Application or output caching is used in software applications to store the results of expensive or time-consuming operations, such as database queries or calculations. The cached results are reused for subsequent requests, improving application performance.
Distributed Caching:

Distributed caching involves caching data across multiple servers or nodes in a distributed computing environment. It enables quick access to data without the need to retrieve it from a central source, reducing latency and improving scalability.
Common File Extensions:

Here are some common file extensions for various types of files:

Executables:

.exe: Executable file in Windows.
.o: Object file in Unix-like systems, used in the compilation process.
.sh: Shell script file in Unix-like systems.
Library files:

.dll: Dynamic Link Library in Windows, containing reusable code.
.so: Shared Object file in Unix-like systems, similar to dynamic libraries in Windows.
.lib: Library file in Windows used for static linking.
Web files:

.html: Hypertext Markup Language file for web pages.
.php: PHP script file for server-side web development.
.css: Cascading Style Sheets file for web page styling.
.js: JavaScript file for client-side web scripting.
Image files:

.jpg or .jpeg: Joint Photographic Experts Group image file.
.svg: Scalable Vector Graphics image file.
.png: Portable Network Graphics image file.
Document files:

.doc: Microsoft Word document file.
.txt: Plain text document file.
.pdf: Portable Document Format file, commonly used for documents that should be viewable and printable on different platforms.
Code files:

.c: C programming language source code file.
.cpp: C++ programming language source code file.
.py: Python programming language source code file.
Key files:

.pub: Public key file, typically used in public-key cryptography.
.pem: Privacy-Enhanced Mail certificate file, often used for secure communication.
.der: Distinguished Encoding Rules file, a binary encoding format often used in security applications.
Understanding these file extensions is essential for working with various types of files and software applications. Different extensions indicate the format and purpose of the files, making it easier to identify and use them appropriately.
