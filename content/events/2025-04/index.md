---
title: 'Custom FTP Server'
date: 2025-04-16T10:54:16-08:00
tags: 
- 2025
- Homer Jones
- Indy
- Installer
---

Homer Jones will show the code for a custom FTP server, the client application that uses it, and the installation script to get this all set up for the end user.

<!--more-->

![](FTP_Users2.png)

Tonight's presentation continues from last month's where Homer will show his custom FTP server that runs as a Windows Service using Indy 10 components. The form-based server discussed last month needed a lot of modifications for logging and error handling. There's a big difference between a form that allows you to see what's going on, and a service that must run unattended in the background, and keep running even when a caveman is the user.

The production client application that uses FTP (Document Manager) will be discussed, including precautions taken to gracefully handle server hiccups. Part of that strategy is being able to switch file access between FTP and File Shares as needed.

Since this will be an upgrade to an existing production application, the installation of the FTP Server as a Windows service will be a little involved. Homer will show how an InnoSetup script installs the server app and not only makes it start automatically upon a Windows reboot but also start immediately upon the completion of the installation.

## PRESENTER ##

HOMER JONES is currently the President of [Agency Business Systems, Incorporated](https://agencybusys.com/), a Portland-based company providing business management software to the Insurance Industry. He has been programming with Delphi since it was first released 30 years ago. 

## DATE/TIME ##

Wednesday, April 16, 2025
6:00 - 8:00 PM

## LOCATION ##

**Olive Garden in Lake Oswego**
[6355 SW Meadows Rd.
Lake Oswego, OR 97035](https://www.olivegarden.com/locations/or/lake-oswego/lake-oswego/1394)
(503) 684-3160