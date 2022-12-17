This guide will walk you through the process of installing C on Mac. If you are using a different operating system, please see the [Getting Started](/Guides/ESC190/Getting Started) page for more information.

## Installing C

### Installing Xcode

The first step is to install Xcode. Xcode is a suite of tools that includes a compiler for C. You can download Xcode from the Mac App Store. Once you have downloaded Xcode, open it and accept the license agreement. You will be prompted to install additional components. Click "Install" to install the additional components.

![Xcode Install](./xcode_install.png)

### Installing Homebrew

The next step is to install Homebrew. Homebrew is a package manager for Mac. It will allow you to easily install and update C. To install Homebrew, open a terminal and run the following command:

```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"```

Once Homebrew is installed, you can install C by running the following command:

```brew install gcc```