# AMC Software Audit

1. [Owned Software](#Owned_Software_5)
2. [Services](#Services_34)

## Owned Software

1.  [Adobe Reader](get.adobe.com/reader/)
    * Adobe reader is the primier utility for viewing .PDF documents and a free offering of Adobe.
    * This is generally installed on all machines including ShoreTel production servers.
1.  [Audacity](audacity.sourceforge.net/download/)
    * Audacity is a quality free audio editing and encoding platform.
    * It's uses include resampling audio files for use in a ShoreTel environment, editing recordings for content and quality, and converting from one audio format to another.
1.  [Google Chrome](http://www.google.com/chrome/browser/desktop/index.html)
    * Google Chrome is the preferred browser for interactions with a mobility router (Though [firefox](https://www.mozilla.org/en-US/) can also be used)
    * Chrome is also viable for working on an ECC and use with ShoreTel 14.2 and earlier Web Communicator clients.
1.  Microsoft Internet Explorer
    * Due to a heavy reliance on ActiveX controls ShoreTel 14.2 and earlier require that Director be run in a current version of IE.
    * IE is installed by default on all Windows machines.
1.  Microsoft Visio
    * Microsoft Visio is the tool of choice for creating and editing network diagrams and system layouts for our records.
    * Ideally every ShoreTel should have a network diagram on record that shows basic IP routing and configuration for all sites and appliances as well as any other relevant network details.
1.  [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)
    * MySQL Workbench is the officially supported MySQL tool for visually inspecting and editing MySQL databases. (Like that which is the core of a ShoreTel system.)
    * The Workbench is a free set of tools that cotains far greater functionality than we typically use, but which is still light-weight enough to make it viable for installation on production servers.
1.  [Paint.net](http://www.getpaint.net/download.html)
    * [Paint.net](http://www.getpaint.net/download.html) is the preferred appliaction for editing, reformating, and converting images. It is a freeware application with enterprise quality tools and documentation.
1.  [Putty](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html)
    * Putty is a multi-purpose terminal emulator, telnet client, ssh client, and serial connection client used for local and remote command line access to switches, appliances, and servers.
1.  [SQLyog Community Edition](https://code.google.com/p/sqlyog/wiki/Downloads)
    * SQLyog CE is a freeware version of the retail software that ShoreTel heavily recommends for accessing and manipulating MySQL databases.
    * SQLyog is a lighter-weight tool than MySQL Workbench, but also has perpetual reminders of the availability of the paid version.


## Services

1. [Dillinger.io](Dillinger.io)
    * Dillinger.io is the preferred web-based Markdown [MD] for AMC.
    * Dillinger.io is not collaborative in the sense of multiple simultaneous editors working on one online document at the same time. But it does allow saving of files in Dropbox, GitHub, Google Drive and OneDrive for file sharing and versioning.
1. [Dropbox.com](Dropbox.com)
    * Dropbox.com is a file-syncing utility.
    * Dropbox.com is generally installed on all technician machines and production servers in order to share files and give access to common tools accross networks.
1. [LogMeIn.com](LogMeIn.com)
    * LogMeIn.com is a remote access utility. By installing a client on the machine which will need to be accessed technicians can gain access remotely through a secured tunnlel initiated from a secured web-site removing the need for a conventional VPN tunnel and client.
    * LogMeIn.com Central is a service allowing us to manage a large quantity of such connections as well as control who has access to what connections from an administrative portal.
1. [Ninite.com](Ninite.com)
    * Ninite.com is an install package that includes multiple utilities which you can select from a list. This enables us to install and update a host of tools and applications which we use regularly more efficiantly.
1. [Orangedox.com](Orangedox.com)
    * Orangedox.com is a front-end for dropbox which allows us to track downloads and more carefully control links to files from within our dropbox.
