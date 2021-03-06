#TicketMiner Addon
Copyright (C) 2016 - Christof Torres, University of Luxembourg

License/usage:
=========================
This software is released under the terms of the MIT license, a copy
of which should be included with this distribution.
This software is provided "AS IS", without any warranties of any kind,
either expressed or implied.

About
=========================
TicketMiner is a proof-of-concept and JavaScript based multi-threaded 
cryptocurrency miner for Mozilla Firefox, allowing users to mine tickets at 
dedicated websites where they can later on redeem these tickets for improved services. Currently the following four mining algorithms are supported:
* Sha256
* Scrypt
* NeoScrypt
* Ethash (Full and Light client)

Screenshots
-----------
### Main Menu
![Main Menu](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-main-menu.png?raw=true "Main Menu")

### Wallet
![Wallet](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-wallet.png?raw=true "Wallet")
![Tickets](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-tickets.png?raw=true "Tickets")

### Miner
![Miner](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-miner.png?raw=true "Miner")
![Miner Not Available](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-miner-not-available.png?raw=true "Miner Not Available")

### Jobs
![Jobs](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-jobs.png?raw=true "Jobs")
![Job](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-job.png?raw=true "Job")

### Settings
![Settings](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-settings.png?raw=true "Settings")

### Donation
![Donation With Balance](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-donation-with-balance.png?raw=true "Donation With Balance")
![Donation Without Balance](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-donation-without-balance.png?raw=true "Donation Without Balance")

### Purchase
![Purchase With Balance](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-purchase-with-balance.png?raw=true "Purchase With Balance")
![Purchase Without Balance](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-purchase-without-balance.png?raw=true "Purchase Without Balance")

Installation instructions
=========================
There are two ways to install the TicketMiner add-on:

1. Compile the source and install the plugin
2. Install the plugin directly from the builds

Compile the source and install the plugin
-----------------------------------------

In order to "compile" the source code to a Mozilla Firefox add-on,
you only need to navigate inside the console to the source folder of the add-on and run the following command:

	jpm xpi

This command packages the add-on as an XPI file, which is the install 
file format for Mozilla Firefox add-ons.

jpm is distributed with the node package manager npm.

There are two ways to get npm:

1. Download and install Node.js from [nodejs.org](https://nodejs.org/en/). Node.js includes npm.
2. Or, if you have a package manager like APT, install npm via that. For example, in an Ubuntu or Debian terminal window, enter: ***sudo apt-get install nodejs nodejs-legacy npm***

After you have npm installed, install jpm just as you would install any other npm package:

	npm install jpm --global

Finally, in order to install the compiled add-on, just drag and drop the XPI
file into the Mozilla Firefox browser. A popup window will appear, asking your approval to install. Click "Install" and you are done. Enjoy!

Install the plugin directly from the builds
-------------------------------------------
To install the plugin directly from the builds, just drag and drop a version of an already pre-compiled XPI file contained inside the "builds" folder into the Mozilla Firefox browser. A popup window will appear, asking your approval to install. Click "Install" and enjoy!
