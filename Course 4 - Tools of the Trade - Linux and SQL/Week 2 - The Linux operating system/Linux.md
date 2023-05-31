# Linux architecture explained
Understanding the Linux architecture is important for a security analyst. When you understand how a system is organized, it makes it easier to understand how it functions. In this reading, you’ll learn more about the individual components in the Linux architecture. A request to complete a task starts with the user and then flows through applications, the shell, the Filesystem Hierarchy Standard, the kernel, and the hardware.

## User
The **user** is the person interacting with a computer. They initiate and manage computer tasks. Linux is a multi-user system, which means that multiple users can use the same resources at the same time.

## Applications
An **application** is a program that performs a specific task. There are many different applications on your computer. Some applications typically come pre-installed on your computer, such as calculators or calendars. Other applications might have to be installed, such as some web browsers or email clients. In Linux, you'll often use a **package manager** to install applications. A package manager is a tool that helps users install, manage, and remove packages or applications. A **package** is a piece of software that can be combined with other packages to form an application.

## Shell
The **shell** is the command-line interpreter. Everything entered into the shell is text based. The shell allows users to give commands to the kernel and receive responses from it. You can think of the shell as a translator between you and your computer. The shell translates the commands you enter so that the computer can perform the tasks you want.

## Filesystem Hierarchy Standard (FHS)
The **Filesystem Hierarchy Standard (FHS)** is the component of the Linux OS that organizes data. It specifies the location where data is stored in the operating system. 

A **directory** is a file that organizes where other files are stored. Directories are sometimes called “folders,” and they can contain files or other directories. The FHS defines how directories, directory contents, and other storage is organized so the operating system knows where to find specific data. 

## Kernel
The **kernel** is the component of the Linux OS that manages processes and memory. It communicates with the applications to route commands. The Linux kernel is unique to the Linux OS and is critical for allocating resources in the system. The kernel controls all major functions of the hardware, which can help get tasks expedited more efficiently.

## Hardware
The **hardware** is the physical components of a computer. You might be familiar with some hardware components, such as hard drives or CPUs. Hardware is categorized as either peripheral or internal.

## Peripheral devices
**Peripheral** devices are hardware components that are attached and controlled by the computer system. They are not core components needed to run the computer system. Peripheral devices can be added or removed freely. Examples of peripheral devices include monitors, printers, the keyboard, and the mouse.

## Internal hardware
**Internal hardware** are the components required to run the computer. Internal hardware includes a main circuit board and all components attached to it. This main circuit board is also called the motherboard. Internal hardware includes the following: 

- The **Central Processing Unit (CPU)** is a computer’s main processor, which is used to perform general computing tasks on a computer. The CPU executes the instructions provided by programs, which enables these programs to run. 

- **Random Access Memory (RAM)** is a hardware component used for short-term memory. It’s where data is stored temporarily as you perform tasks on your computer. For example, if you’re writing a report on your computer, the data needed for this is stored in RAM. After you’ve finished writing the report and closed down that program, this data is deleted from RAM. Information in RAM cannot be accessed once the computer has been turned off. The CPU takes the data from RAM to run programs. 

- The **hard drive** is a hardware component used for long-term memory. It’s where programs and files are stored for the computer to access later. Information on the hard drive can be accessed even after a computer has been turned off and on again. A computer can have multiple hard drives.

## Key takeaways
It’s important for security analysts to understand the Linux architecture and how these components are organized. The components of the Linux architecture are the user, applications, shell, Filesystem Hierarchy Standard, kernel, and hardware. Each of these components is important in how Linux functions. 

---

# More Linux distributions
Previously, you were introduced to the different distributions of Linux. This included KALI LINUX ™. (KALI LINUX ™ is a trademark of OffSec.) In addition to KALI LINUX ™, there are multiple other Linux distributions that security analysts should be familiar with. In this reading, you’ll learn about additional Linux distributions.

## KALI LINUX ™
KALI LINUX ™ is an open-source distribution of Linux that is widely used in the security industry. This is because KALI LINUX ™, which is Debian-based, is pre-installed with many useful tools for penetration testing and digital forensics. A **penetration test** is a simulated attack that helps identify vulnerabilities in systems, networks, websites, applications, and processes. **Digital forensics** is the practice of collecting and analyzing data to determine what has happened after an attack. These are key activities in the security industry. 

However, KALI LINUX ™ is not the only Linux distribution that is used in cybersecurity. 

## Ubuntu
**Ubuntu** is an open-source, user-friendly distribution that is widely used in security and other industries. It has both a command-line interface (CLI) and a graphical user interface (GUI). Ubuntu is also Debian-derived and includes common applications by default. Users can also download many more applications from a package manager, including security-focused tools. Because of its wide use, Ubuntu has an especially large number of community resources to support users.

Ubuntu is also widely used for cloud computing. As organizations migrate to cloud servers, cybersecurity work may more regularly involve Ubuntu derivatives.

## Parrot
**Parrot** is an open-source distribution that is commonly used for security. Similar to KALI LINUX ™, Parrot comes with pre-installed tools related to penetration testing and digital forensics. Like both KALI LINUX ™ and Ubuntu, it is based on Debian.

Parrot is also considered to be a user-friendly Linux distribution. This is because it has a GUI that many find easy to navigate. This is in addition to Parrot’s CLI.

## Red Hat® Enterprise Linux®
**Red Hat Enterprise Linux** is a subscription-based distribution of Linux built for enterprise use. Red Hat is not free, which is a major difference from the previously mentioned distributions. Because it’s built and supported for enterprise use, Red Hat also offers a dedicated support team for customers to call about issues.

## CentOS
**CentOS** is an open-source distribution that is closely related to Red Hat. It uses source code published by Red Hat to provide a similar platform. However, CentOS does not offer the same enterprise support that Red Hat provides and is supported through the community.

## Key takeaways
KALI LINUX ™, Ubuntu, Parrot, Red Hat, and CentOS are all widely used Linux distributions. It’s important for security analysts to be aware of these distributions that they might encounter in their career.

---

# [Resources for completing Linux labs]https://www.coursera.org/learn/linux-and-sql/supplement/uLa2R/resources-for-completing-linux-labs)
This course features hands-on lab activities where you'll have the opportunity to practice Linux commands in the terminal. You’ll use a platform called Qwiklabs to complete these labs. In this reading, you’ll learn how to use Qwiklabs.

## How to use Qwiklabs
**Launching Qwiklabs**
When you select a lab, you start from a Coursera page. You will need to click **Launch App** on that page. After you click **Launch App**, a new tab will open with a Qwiklabs page that contains instructions for that particular lab.  

## Start Lab button
On the Qwiklabs page, you must click **Start Lab** to open a temporary terminal. The instructions for the lab will move to the right side of the screen.

![Green button with text “Start Lab” and a maximum time limit of 20 minutes displayed.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/bbLYK8KXTheEmp-pArlF-g_ef7afc94b9304f30844a19e45e922ff1_wPU2KdBxIZhEA0euFsDlhs_nHve2ceZ69LNUPx4ZE0Bb8jVXhx-Qq2dfRIK1a8IFwZ08_GkPEgh4NR_8yvGYvn0U4FTm6l8QGhpbBlTwXew2thU31_64Ivi7nwPKJNCtemriZhtJWAfZdc0dQ-tTfEo?expiry=1685577600000&hmac=ArKcdjlYFMyN8X3mtkG1R6Wqihh__3wzd8qEyokCYPk)

Read the instructions and complete all the tasks in the lab by entering commands in the terminal.

**Note**: It may take a moment for the terminal to start.

## Lab control dialog box
After you click **Start Lab**, the lab control dialog box opens. It contains the **End Lab** button, the **timer**, and the **Open Linux Console** button.

You can hide or unhide the dialog box by clicking the following icon in the red box:

![Four rectangles spiraling next to each other to comprise one square surrounded by a red box in a screenshot of the lab.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/9J3KUOFWRNWzekD6Uiykyg_f489a579c31c4a8b8c2f9b68467495f1_LuMypehj-sqYyJlYCJGk-0LPWQirKP_cVeCYhsw1ism9amvqsYDhZEdh-Wyzh1tW__cut8UToAifaNs6LRj3iXCr4ujUo_RA7h-qx4rJVs1CRjAwAwCGM-gnKcx4wIWeV2b9IqCRB14qOVyda1LeQDA?expiry=1685577600000&hmac=gUr64aY2aYOBLNVC3wKz1n5lEs4iSeYQB_llYWv2q44)

## The timer
The **timer** starts when the terminal has loaded. The timer keeps track of the amount of time you have left to complete a lab. The timer counts down until it reaches 00:00:00. When it does, your temporary terminal and resources are deleted.

You will have ample time to complete the labs. But, stay focused on completing the tasks to ensure you use your time well.

## Open Linux Console button
When you click the button to **Open Linux Console**, the terminal opens in a new browser window:

[A red square around a button with text “Open Linux Console”.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/GL_lszqoS_SwMddGbzYgEQ_1bd87af68f5f46a0be668b190f51f6f1_tEIGaT6dW10ie3BjpmzvFivoi8feEG9-Iw7O_lAjvdvWpFXlZOm8HmiNc2c9OgRKvKUBjJhp8HfoR3qu9JPY4GzGbCSOvh_nC-pKywu_G0B7V_ULMpjKTT06CYfx4b7oS1HPZnudcST_D-LjQmdIwmY?expiry=1685577600000&hmac=ZJxJMfvWcoHnXJ1VSkMaJ5RZ2JgKl1Zezz_JF_okElI)

Use this feature if you want a full-screen view of the terminal. You can close this window at any time. Closing the window does not end your lab, and you can continue working in the terminal in the original tab.

## Check progress
You can check your progress by clicking **Check my progress** at the end of each task.

![Blue button with text “Check my progress” below a sample task.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/IbOfFeajT2q9yZWHyXxHOA_e8b0749220334c5aa3ac5f0aa7070ef1_kN58Isr_cUeyITXiw1gAqBQeWHP4UIaMnQbwyVY6sRQre_L0gtmYjALeqKvApc1L8XchdZeLsfUaNwA9aQZL0Kir1h0c8BJjGsKWq8mfHEmrS0pVNBb4h5c-3hJ-__kbwaa0LN5U8CbJBLlqWToABF0?expiry=1685577600000&hmac=rMIV1Lp_mDWj0ubho6oVCgC5zecJMg9dkJRIYp-jUSo)

If you haven’t yet completed a task, you’ll receive hints on what you must do to complete it.

You can click **Check my progress** whenever you want to check the completion status of a task or receive a hint.

## Using copy/paste commands
The first time you try to use copy or paste keyboard shortcuts (such as **CTRL + C**), you’ll receive a pop-up requesting permission to use your device’s clipboard:  “**googlecoursera.qwiklabs.com wants to see text and images copied to the clipboard.**” Please click **Allow** if you would like to be able to use these shortcuts in the Qwiklabs platform. If you choose not to allow Qwiklabs access to your clipboard, you cannot use keyboard shortcuts but you can still complete the lab.

## Code block
Certain steps may include a code block. Click the copy button to copy the code provided and then paste it into the terminal.

![Two layered rectangles surrounded by a red box on the right side of a sample code block to indicate copy.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/tSaH4Zd2T9qHv2ALlr1fGA_a4c26fdc722a4b3c8f38f12e15c863f1_OhCX3BSN-yf0Nd8lnjLLk4t5hUVBbpR913lAp_yIdqsaOEgDIiV-p9N2nflw4o4ED_Fwxsg6Dez7gopRSYphMueEEoblkkIBY3ELnRDiqKhC6ZILGCJH1NSugmPxU2Y50M2sGk98kdv--GwRMchPRJU?expiry=1685577600000&hmac=VGESAprb445_2NIYO3UtcS4MInTbU58uGIiYadmS0TM)

To paste code or other text content that you have copied from the instructions into the terminal, activate the terminal by clicking anywhere inside it. The terminal is active when the cursor in the terminal changes from a static empty outline to a flashing solid block.

![A dollar sign prompt and white rectangle cursor surrounded by a red box in the terminal.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/cgjBaqtES0ayrgvTCk3QZQ_25005fa6300f4d1ba01ef6a768097ef1_NCn3RU6ab8eSTxYYo2V1zh5y2ehRWaP-OavQGkZpJgxI-K-JeeIL5QSJCMqQqMQ-09eapv_GCAub7jZG6zmqX3VZ3Vx59qV_qXdJVo4LUqGW2kQz36DXIGk17rzkSmMmPvVRlrMp3nfeoC9dbYjk98Q?expiry=1685577600000&hmac=YO5XN2KpEdyE6t1hPS10bu1-X6hYQyMHvDTuG_7GG7M)

Once the terminal is active, use the keyboard shortcut **CTRL + V** (hold down the **CTRL** key and press the V key) to insert the copied text into the terminal at the location of the flashing cursor.

## Scrolling
In certain situations, you may want to scroll within the terminal window. To do so, use the scroll wheel on your mouse or the touchpad of your computer.

## End Lab button

![A red button with text “End Lab” surrounded by a red box.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/dN9wPgYMQl2fBxFAffoZjw_38694553980f42cd94d8906a1f2d1bf1_Mfw27huMPvdOZI21TbioE29m49cakKuRkC3cEtNpIUkdnVMw7P8r1N9ETGXSSloVpG_zhsBqeA4uj7RTVMTFLChkhBUdF4yYkeIfa5Y42X6AWHf7HrQqiBm9sPcDBpY2pxdpvQVQRQSvbQbmCS43wY8?expiry=1685577600000&hmac=dsSd1qHONO3D1Gf7qrY6YG6YWk0W8CkjJKLOkLeNQdY)

Finally, click **End Lab** when you’ve completed the tasks in the lab.

**Note:** Don't click **End Lab** until you're finished; you'll lose access to the work you've done throughout the lab.

## Tracking progress on Coursera
If you complete a lab but your progress hasn’t been tracked on Coursera, you may need to refresh the page for your progress to be registered. Once you complete the lab and refresh the page, the green check mark should appear.

## Key takeaways
Knowing how to navigate Qwiklabs will be useful as you complete the labs throughout this course. These labs can help you practice what you’ve learned in an interactive environment.

---

# Activity: Install software in a Linux distribution
## Introduction
In this lab, you’ll learn how to install and uninstall applications in Linux. You’ll use Linux commands in the Bash shell to complete this lab. You’ll also use the Advanced Package Tool (APT) package manager to install and uninstall the Suricata and tcpdump applications.

## What you’ll do
You have multiple tasks in this lab:

- Confirm APT is installed in Bash

- Install Suricata with APT

- Uninstall Suricata with APT

- Install tcpdump with APT

- Reinstall Suricata with APT

## Lab instructions
### Start the lab
Before you start, you can review the [Resources for completing Linux labs](https://www.coursera.org/learn/linux-and-sql/supplement/uLa2R/resources-for-completing-linux-labs). Then from this page, click Launch App. A Qwiklabs page will open and from that page, click **Start Lab** to begin the activity!

*You may attempt this lab a maximum of 5 times, and you will have 60 minutes to complete this lab during each attempt.*

**End the lab**
From within the lab, click **End Lab** to end your lab. 

Additionally, sometimes you need to refresh your Coursera page in order for your progress to be registered. If you refresh this page after you complete your lab, the green check mark should appear.

This course uses a third-party app, Activity: Install software in a Linux distribution, to enhance your learning experience. The app will reference basic information like your name, email, and Coursera ID.