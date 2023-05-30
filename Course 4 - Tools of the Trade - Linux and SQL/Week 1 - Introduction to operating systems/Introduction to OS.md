# Compare operating systems
You previously explored why operating systems are an important part of how a computer works.  In this reading, you’ll compare some popular operating systems used today. You’ll also focus on the risks of using legacy operating systems.

## Common operating systems
The following operating systems are useful to know in the security industry: Windows, macOS®, Linux, ChromeOS, Android, and iOS.

### Windows and macOS
Windows and macOS are both common operating systems. The Windows operating system was introduced in 1985, and macOS was introduced in 1984. Both operating systems are used in personal and enterprise computers. 

Windows is a closed-source operating system, which means the source code is not shared freely with the public. macOS is partially open source. It has some open-source components, such as macOS’s kernel. macOS also has some closed-source components. 

### Linux
The first version of Linux was released in 1991, and other major releases followed in the early 1990s. Linux is a completely open-source operating system, which means that anyone can access Linux and its source code. The open-source nature of Linux allows developers in the Linux community to collaborate.

Linux is particularly important to the security industry. There are some distributions that are specifically designed for security. Later in this course, you’ll learn about Linux and its importance to the security industry.

### ChromeOS
ChromeOS launched in 2011. It’s partially open source and is derived from Chromium OS, which is completely open source. ChromeOS is frequently used in the education field.

### Android and iOS
Android and iOS are both mobile operating systems. Unlike the other operating systems mentioned, mobile operating systems are typically used in mobile devices, such as phones, tablets, and watches. Android was introduced for public use in 2008, and iOS was introduced in 2007. Android is open source, and iOS is partially open source.

## Operating systems and vulnerabilities
Security issues are inevitable with all operating systems. An important part of protecting an operating system is keeping the system and all of its components up to date.

### Legacy operating systems
A **legacy operating system** is an operating system that is outdated but still being used. Some organizations continue to use legacy operating systems because software they rely on is not compatible with newer operating systems. This can be more common in industries that use a lot of equipment that requires embedded software—software that’s placed inside components of the equipment.

Legacy operating systems can be vulnerable to security issues because they’re no longer supported or updated. This means that legacy operating systems might be vulnerable to new threats. 

### Other vulnerabilities
Even when operating systems are kept up to date, they can still become vulnerable to attack. Below are several resources that include information on operating systems and their vulnerabilities.

- [Microsoft Security Response Center (MSRC)](https://msrc.microsoft.com/update-guide/vulnerability): A list of known vulnerabilities affecting Microsoft products and services

- [Apple Security Updates](https://support.apple.com/en-us/HT201222): A list of security updates and information for Apple® operating systems, including macOS and iOS, and other products

- [Common Vulnerabilities and Exposures (CVE) Report for Ubuntu](https://ubuntu.com/security/cves): A list of known vulnerabilities affecting Ubuntu, which is a specific distribution of Linux

- [Google Cloud Security Bulletin](https://cloud.google.com/support/bulletins): A list of known vulnerabilities affecting Google Cloud products and services

Keeping an operating system up to date is one key way to help the system stay secure. Because it can be difficult to keep all systems updated at all times, it’s important for security analysts to be knowledgeable about legacy operating systems and the risks they can create.

## Key takeaways
Windows, macOS, Linux, ChromeOS, Android, and iOS are all commonly used operating systems. Security analysts should be aware of vulnerabilities that affect operating systems. It’s especially important for security analysts to be familiar with legacy operating systems, which are systems that are outdated but still being used. 

---

# Requests to the operating system
Operating systems are a critical component of a computer. They make connections between applications and hardware to allow users to perform tasks. In this reading, you’ll explore this complex process further and consider it using a new analogy and a new example.

## Booting the computer
When you boot, or turn on, your computer, either a BIOS or UEFI microchip is activated. The **Basic Input/Output System (BIOS)** is a microchip that contains loading instructions for the computer and is prevalent in older systems. The **Unified Extensible Firmware Interface (UEFI)** is a microchip that contains loading instructions for the computer and replaces BIOS on more modern systems.

The BIOS and UEFI chips both perform the same function for booting the computer. BIOS was the standard chip until 2007, when UEFI chips increased in use. Now, most new computers include a UEFI chip. UEFI provides enhanced security features.

The BIOS or UEFI microchips contain a variety of loading instructions for the computer to follow. For example, one of the loading instructions is to verify the health of the computer’s hardware.

The last instruction from the BIOS or UEFI activates the bootloader. The **bootloader** is a software program that boots the operating system. Once the operating system has finished booting, your computer is ready for use.

## Completing a task
As previously discussed, operating systems help us use computers more efficiently. Once a computer has gone through the booting process, completing a task on a computer is a four-part process.

![Shows a process that moves from user to application to operating systems and finally to hardware.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/bfvQyeg_SC-DSgUsegf8PQ_8405d4e94af147e1b98df5150c2fd7f1_CS_R-060_User-Application-Operating-System-Hardware.png?expiry=1685577600000&hmac=EG5K2BP2DD0UjdfWv0WqCtWKuk2b5kXtPtK-mTD9b6s)

## User
The first part of the process is the user. The user initiates the process by having something they want to accomplish on the computer. Right now, you’re a user!  You’ve initiated the process of accessing this reading.

## Application
The application is the software program that users interact with to complete a task. For example, if you want to calculate something, you would use the calculator application. If you want to write a report, you would use a word processing application. This is the second part of the process.

## Operating system
The operating system receives the user’s request from the application. It’s the operating system’s job to interpret the request and direct its flow. In order to complete the task, the operating system sends it on to applicable components of the hardware. 

## Hardware
The hardware is where all the processing is done to complete the tasks initiated by the user. For example, when a user wants to calculate a number, the CPU figures out the answer. As another example, when a user wants to save a file, another component of the hardware, the hard drive, handles this task. 

After the work is done by the hardware, it sends the output back through the operating system to the application so that it can display the results to the user.

## The OS at work behind the scenes
Consider once again how a computer is similar to a car. There are processes that someone won’t directly observe when operating a car, but they do feel it move forward when they press the gas pedal. It’s the same with a computer. Important work happens inside a computer that you don’t experience directly. This work involves the operating system.

You can explore this through another analogy. The process of using an operating system is also similar to ordering at a restaurant. At a restaurant you place an order and get your food, but you don’t see what’s happening in the kitchen when the cooks prepare the food.

Ordering food is similar to using an application on a computer. When you order your food, you make a specific request like “a small soup, very hot.” When you use an application, you also make specific requests like “print three double-sided copies of this document.” 

You can compare the food you receive to what happens when the hardware sends output. You receive the food that you ordered. You receive the document that you wanted to print. 

Finally, the kitchen is like the OS. You don’t know what happens in the kitchen, but it’s critical in interpreting the request and ensuring you receive what you ordered. Similarly, though the work of the OS is not directly transparent to you, it’s critical in completing your tasks.

## An example: Downloading a file from an internet browser
Previously, you explored how operating systems, applications, and hardware work together by  examining a task involving a calculation. You can expand this understanding by exploring how the OS completes another task, downloading a file from an internet browser: 

- First, the user decides they want to download a file that they found online, so they click on a download button near the file in the internet browser application.

- Then, the internet browser communicates this action to the OS.

- The OS sends the request to download the file to the appropriate hardware for processing.

- The hardware begins downloading the file, and the OS sends this information to the internet browser application. The internet browser then informs the user when the file has been downloaded.

## Key takeaways
Although it operates in the background, the operating system is an essential part of the process of using a computer. The operating system connects applications and hardware to allow users to complete a task.

---

# The command line in use
Previously, you explored graphical user interfaces (GUI) and command-line user interfaces (CLI). In this reading, you’ll compare these two interfaces and learn more about how they’re used in cybersecurity.  

## CLI vs. GUI
A **graphical user interface (GUI)** is a user interface that uses icons on the screen to manage different tasks on the computer. A **command-line interface (CLI)** is a text-based user interface that uses commands to interact with the computer. 

### Display
One notable difference between these two interfaces is how they appear on the screen. A GUI has graphics and icons, such as the icons on your desktop or taskbar for launching programs. In contrast, a CLI only has text. It looks similar to lines of code. 

![Side by side comparison of a graphical user interface with icons and a command line interface with code.](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/jPiBzy6QRUC9BFKsrZSzXQ_9657c9ea0df1405aa8ba6fa1639f7bf1_Eq1sask98GT1PJWgAlVVsdoJ4BUZUA19gHHuvnwl9z5e3KfXeQ1vBp7IN8d19BsiN9mYkEWBY_x_jxXBN9NjvXa_fOEwuLWdr8JKi-Uk8ztLWl0Wm4PvLdipIryGpvtv-qMJ6WT6R2kDGXxSeF-ZJStysiZtPxlectb2JtueXryWq9cQ1Sy8YwTnUPwozg?expiry=1685577600000&hmac=95Y452-MAAPj19N_6-NQyxV_oz6jwkaIgtj5HoNv6tU)

### Function
These two interfaces also differ in how they function. A GUI is an interface that only allows you to make one request at a time. However, a CLI allows you to make multiple requests at a time. 

## Advantages of a CLI in cybersecurity  
The choice between using a GUI or CLI is partly based on personal preference, but security analysts should be able to use both interfaces. Using a CLI can provide certain advantages.

### Efficiency
Some prefer the CLI because it can be used more quickly when you know how to manage this interface. For a new user, a GUI might be more efficient because they’re easier for beginners to navigate. 

Because a CLI can accept multiple requests at one time, it’s more powerful when you need to perform multiple tasks efficiently. For example, if you had to create multiple new files in your system, you could quickly perform this task in a CLI. If you were using a GUI, this could take much longer, because you have to repeat the same steps for each new file.

### History file
For security analysts, using the Linux CLI is helpful because it records a history file of all the commands and actions in the CLI. If you were using a GUI, your actions are not necessarily saved in a history file.

For example, you might be in a situation where you’re responding to an incident using a playbook. The playbook’s instructions require you to run a series of different commands. If you used a CLI, you’d be able to go back to the history and ensure all of the commands were correctly used. This could be helpful if there were issues using the playbook and you had to review the steps you performed in the command line.

Additionally, if you suspect an attacker has compromised your system, you might be able to trace their actions using the history file.

## Key takeaways
GUIs and CLIs are two types of user interfaces that security analysts should be familiar with. There are multiple differences between a GUI and a CLI, including their displays and how they function. When working in cybersecurity, a CLI is often preferred over a GUI because it can handle multiple tasks simultaneously and it includes a history file.

