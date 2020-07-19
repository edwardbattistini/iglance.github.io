---
layout: post
title: Release notes
permalink: /release-notes.html
show: true
subtitle: "iGlance is developped by a community of blablabal "
date: '2020-03-05 11:15:33'
hero-size: is-medium
date: '2020-03-05 16:43:18'
background-colour: is-info
---
### Version 2.0.9 (2020-06-29)

#### New features:

*   Memory information matches now the information in the Activity Monitor app

#### Bug fixes:

*   Fixed a bug that would cause the app to not start after login
*   Fixed a bug that would cause the app to immediately crash after starting it
*   Fixed a bug that would dismiss the battery notifications to fast
*   Fixed a memory leak
*   Fixed a bug that would cause option "Show disk space usage" to be always ticked when reloading the view (thank you [@gary-lgy](https://github.com/gary-lgy))

### Version 2.0.8 (2020-04-26)

#### New features:

*   It is now possible to export, import and reset the settings of the app under the app menu 'File' (thank you [@Moneypulation](https://github.com/Moneypulation))
*   It is now possible to display the used and free disk space in the menu bar (thank you [@khorolets](https://github.com/khorolets))

#### Bug fixes:

*   Fixed a bug that would cause the app to display wrong system information on the dashboard
*   Fix a bug that would cause the app to randomly crash
*   Fixed a bug that would prevent the app from showing a popup for a new update

### Version 2.0.7 (2020-04-21)

#### Bug/Hot fix:

*   This version provides a hot-fix for random crashes
*   Fixed a bug that would not set the update interval correctly when changed

### Version 2.0.6 (2020-04-20)

#### Bug fixes:

*   Fixed a bug that would cause the cpu usage graph to spike to 100% while the actual usage is 0%
*   Fixed a bug that would not correctly display the "Show network usage" checkbox
*   Fixed a bug that would cause the network menu bar to display a bandwidth of zero while connected to a VPN
*   Fixed a bug that would cause iGlance to freeze after the machine was sleeping

### Version 2.0.5 (2020-04-16)

#### New features:

*   It is now possible to export the most recent log file using \`Diagnostics > Save Logfile...\` in the app menu
*   It is now possible to open the preferences of the app using iGlance > Preferences in the app menu or by pressing CMD + , while the iGlance window is active

#### Bug fixes:

*   Fixed a bug that would show the wrong available memory in the menu of the memory menu bar item
*   Fixed a bug that would cause the app to freeze after waking the machine from sleep
*   Fixed a bug that would cause the cpu bar graph to be fully drawn while the machine is not under load

### Version 2.0.4 (2020-04-01)

*   The update prompt now displays the release notes
*   Fixed bug that would show a cpu temperature of -1 on some machines
*   Fixed the app diagnostics menu
*   The system font is now used to render text on the menu bar items

### Version 2.0.4 (2020-04-01)

*   The update prompt now displays the release notes
*   Fixed bug that would show a cpu temperature of -1 on some machines
*   Fixed the app diagnostics menu
*   The system font is now used to render text on the menu bar items

### Version 2.0.3 (2020-03-29)

*   The setting Advanced Logging is now saved when quitting the app
*   The app doesn't crash anymore when changing the network interface (e.g. when connecting to a VPN)

### Version 2.0.2 (2020-03-29)

*   Hotfix🔥: Fixed a bug that would cause the app to crash immediately after launch

### Version 2.0.1 (2020-03-29)

*   Hotfix🔥: App is now starting on machines that have no NVMe drive

### Version 2.0.0 (2020-03-28)

*   New GUI
*   App is now automatically updated using [Sparkle](https://sparkle-project.org)
*   [AppMover](https://github.com/iglance/AppMover) asks to move the app into the Applications folder on startup
*   The percentage of the battery can now be displayed in the menu bar
*   When displaying the remaining chargin/discharging time, the current status of the battery while charging is displayed (Not Charging, Charging, Charged)
*   The total transmitted data is now displayed in the network menu
*   The app is now published under the GNU GPLv3 license