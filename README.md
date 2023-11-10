
### Very Basic Computer Fundamentals
* **Basic BIOS Configurations**
  * **Boot Sequence :**<br>
  The boot sequence determines the order in which the computer checks for and boots from different storage devices (e.g., hard drive, USB drive, CD/DVD drive).
  * **Enabling / Disabling Devices :** <br/>
   BIOS settings allow users to enable or disable various hardware components, such as USB ports, integrated audio, onboard graphics, or network adapters.
  * **Changing Date / Time :** <br/>
   BIOS includes a real-time clock (RTC) that keeps track of the system's date and time. Users can set or adjust the date and time in BIOS to ensure accurate timestamps for files and system logs.
    * **CMOS Batteries :**<br/>
    BIOS settings are stored in CMOS (Complementary Metal-Oxide-Semiconductor) memory, which requires a small battery to maintain these settings even when the computer is powered off.
  * **CPU Clockspeeds :**<br/>
  BIOS allows users to configure CPU clockspeed settings, including the base clock frequency and the multiplier. Overclocking enthusiasts often use these settings to increase CPU performance.
  * **BIOS Firmware Upgrades :**<br/>
  Often referred to as BIOS updates or flashing the BIOS, involve updating the firmware on the motherboard to add new features, improve compatibility, or fix security vulnerabilities. This process should be done with caution.
  * **Enabling Virtualization Support :**<br/>
  Some CPUs support hardware-assisted virtualization, which is crucial for running virtual machines efficiently. In BIOS, users can enable or disable virtualization technology (e.g., Intel VT-x or AMD-V) to enhance virtualization performance.
  * **Secure Boot _(Basic Understanding)_ :**<br/>
  Secure Boot is a security feature that prevents the loading of unauthorized or malicious software during the boot process. It verifies the digital signatures of bootloader files to ensure they haven't been tampered with. Users can typically enable or disable Secure Boot in BIOS.

* **Hard Drive Basics**
  * **Magnetic HDDs :**<br/>
  Magnetic HDDs use spinning platters coated with a magnetic material to store data. An actuator arm with read/write heads moves over the platters to read or write data. They provide high-capacity storage at a lower cost but are slower and less durable than SSDs.
  * **SSDs :**<br/>
  SSDs use NAND flash memory to store data. They are faster, more energy-efficient, and durable than HDDs because they have no moving parts
  * **eMMC :**<br/>
  eMMC is a type of flash storage used in many mobile devices and budget laptops. It's an integrated solution where the storage and controller are combined into a single chip. While eMMC is cost-effective, it's slower than SSDs.
  
* **Partitioning :** <br/>
  Partitioning involves dividing a hard drive or SSD into multiple logical sections or partitions. Partitions can help organize data, separate the operating system from user data, or facilitate multi-boot setups.
    * **FAT32 :**<br/>
    FAT32 is a file system format that can be used for storing files on hard drives, USB drives, and memory cards. It's a simple and widely compatible format but has limitations, such as a maximum file size of 4 GB.
    * **NTFS :**<br/>
    NTFS is a file system format used primarily in Windows operating systems. It offers features like file compression, encryption, access control
    * **ext2, ext3, ext4 :**<br/>
    These are file system formats used in Linux and other Unix-like operating systems, ext4 is the most commonly used version today.
  * **MBR _(Legacy)_  :**<br/>
  MBR is a legacy boot sector that was widely used to manage partition information and bootloaders in older computer systems.
  * **EFI / UEFI :**<br/>
  EFI/UEFI is a modern replacement for the traditional BIOS. It provides an interface between the operating system and the hardware. UEFI is more secure and versatile, supporting larger hard drives and newer security features like Secure Boot.<br/>
 
* **RAM**<br/>
  RAM is volatile computer memory used for temporarily storing data that the CPU is actively using. It allows for quick access and retrieval of data, significantly faster than reading from a storage drive.
  * **DDR1, DDR2, DDR3, DDR4 :**<br/>
  These are different generations of DDR RAM. Each generation offers increased data transfer rates and efficiency.
  * **Memory Speeds :**<br/>
  Memory speed, measured in MHz (megahertz), indicates how quickly data can be read from or written to RAM. Higher MHz values mean faster memory
  * **Memory Addressing :**<br/>
  Memory addressing refers to the system's ability to locate and access specific memory locations. 32-bit systems can address up to 4 GB of RAM
* **CPUs**<br/>
CPUs are the "brains" of a computer and execute instructions. They come in various brands and models.
  * **Intel:**<br/>
  
    * **i3, i5, i7, i9:**<br/>
    Intel offers a range of processors, including:
i3: Entry-level processors.
i5: Mid-range processors.
i7: High-end processors.
i9: Enthusiast processors with high performance and more cores/threads.
AMD CPUs:
  * **AMD:**<br/>
  
    * **Ryzen 3, Ryzen 5, Ryzen 7, Ryzen 9:**<br/>
    Ryzen 3: Entry-level processors.
Ryzen 5: Mid-range processors.
Ryzen 7: High-performance processors.
Ryzen 9: High-end processors with multiple cores and threads.
  * **32bit CPUs:**<br/>
  These CPUs can address a maximum of 4 GB of RAM. They are limited in terms of memory capacity and are less common in modern computers.
  * **64bit CPUs:**<br/>
  These CPUs can address significantly more RAM, making them suitable for modern computing. They are more common in today's systems.
  * **MultiThreading vs. MultiProcessing:**<br/>
  MultiThreading refers to a CPU's ability to handle multiple threads (tasks) simultaneously, improving performance and multitasking. MultiProcessing, on the other hand, involves multiple physical processors (or CPU cores) in a system, allowing it to process multiple tasks independently.
* **GPUs**<br/>
GPUs are specialized processors designed for rendering graphics and performing parallel processing tasks.
  * **Integrated vs. Discrete GPUs**<br/>
  Integrated GPUs are built into the CPU or motherboard and share system RAM.<br/>
  Discrete GPUs are separate graphics cards with dedicated VRAM and offer higher performance for gaming and graphics-intensive tasks.
  * **Ray Tracing :**<br/>
  Ray tracing is a rendering technique that simulates how light interacts with objects to create highly realistic graphics. It's used in modern GPUs to enhance graphics quality.
  * **GPU Memory :**<br/>
  GPU memory (VRAM) is dedicated memory used by the GPU for rendering and storing textures and other graphics data. More VRAM can improve performance in graphics-intensive applications.
  * **GPU Bandwidth :**<br/>
  GPU bandwidth is the rate at which data can be transferred to and from the GPU's memory. Higher bandwidth allows for faster data access and rendering, improving GPU performance.
* **Caching**<br/>
Caching is a technique used in computing to store and reuse data or resources to speed up access and reduce the load on the original data source. There are various types of caching:
  * **Web Caching :**<br/>
  Involves storing web content (HTML pages, images, stylesheets, etc.) at intermediate points, like web proxies or Content Delivery Networks (CDNs). Cached content can be quickly delivered to users.
  * **Data Caching :**<br/>
  Data caching is used to store frequently accessed data in a faster, more easily retrievable location, such as RAM.
  * **Application/Output Caching :**<br/>
  Application or output caching is used in software applications to store the results of expensive or time-consuming operations, such as database queries or calculations. The cached results are reused for subsequent requests.
  * **Distributed Caching :**<br/>
  Distributed caching involves caching data across multiple servers or nodes in a distributed computing environment. It enables quick access to data without the need to retrieve it from a central source.
* **Common File Exstentions**<br/>

  * **Executables**
    * **.exe :** Executable file in Windows.
    * **.o :**   Object file in Unix-like systems, used in the compilation process.
    * **.sh :**  Shell script file in Unix-like systems.
  * **Library files*
    * **.dll :** Dynamic Link Library in Windows, containing reusable code.
    * **.so :**  Shared Object file in Unix-like systems, similar to dynamic libraries in Windows.
    * **.lib :** Library file in Windows used for static linking.
  * **Web files**
    * **.html :** Hypertext Markup Language file for web pages.
    * **.php :** PHP script file for server-side web development.
    * **.css :** Cascading Style Sheets file for web page styling.
    * **.js :**  JavaScript file for client-side web scripting.
  * **Image files**
    * **.jpg or .jpeg :** Joint Photographic Experts Group image file.
    * **.svg :** Scalable Vector Graphics image file. 
    * **.png :** Portable Network Graphics image file.
  * **Document files**
    * **.doc :** Microsoft Word document file.
    * **.txt :**  Plain text document file.
    * **.pdf :** Portable Document Format file, used for documents that should be viewable and printable on different platforms.
  * **Key files**
    * **.pub :** Public key file, typically used in public-key cryptography.
    * **.pem :** Privacy-Enhanced Mail certificate file, often used for secure communication.
    * **.der :** Distinguished Encoding Rules file, a binary encoding format often used in security applications.
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


  
