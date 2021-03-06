#TicketMiner
Copyright (C) 2016 - Christof Torres, University of Luxembourg

License/usage:
=========================
This software is released under the terms of the MIT license, a copy
of which should be included with this distribution.
This software is provided "AS IS", without any warranties of any kind,
either expressed or implied.

About
=========================
This is a Master project founded by the [CryptoLUX research team](https://www.cryptolux.org/index.php/Home) within the Computer Science and Communications (CSC) research unit of the Faculty of Science, Technology and Communication (FSTC) at the University of Luxembourg.

TicketMiner is a proof-of-concept based on the paper ["Proof-of-Work as Anonymous Micropayment: Rewarding a Tor Relay" [1]](https://www.cryptolux.org/images/3/3e/Alex-ivan-tor-micropayments.pdf) by Prof. Dr. Alex Biryukov and Dr. Ivan Pustogarov, allowing users to mine shares through their browser for specific websites and getting back in return tickets which they can either redeem for improved services or donate to websites.

[Server](../master/Server)
------
The TicketMiner server application is a Node.js application and can be found inside the "Server" directory. The server runs in the background on the website wishing to provide improved services or receive donations by TicketMiner clients. 

![Dashboard](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Server/screenshots/screen-dashboard.png?raw=true "Dashboard")

[Client](../master/Addon)
------
The TicketMiner client application is a Mozilla Firefox add-on that runs inside the Firefox browser and mines tickets from TicketMiner enabled websites. The client can be found inside the "Addon" directory.

![Main Menu](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-main-menu.png?raw=true "Main Menu")
![Wallet](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-wallet.png?raw=true "Wallet")
![Miner](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-miner.png?raw=true "Miner")
![Job](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/Addon/screenshots/screen-job.png?raw=true "Job")

[Test Cases](../master/TestCases)
----------
In addition, this project also includes two test cases, illustrating two possible use cases of TicketMiner services, namely donations and mirco-payments inside e-commerce websites. These two test cases can be found inside the "TestCases" directory.

![Large Coffee](https://raw.githubusercontent.com/christoftorres/TicketMiner/master/TestCases/screenshots/screen-large-coffee.png?raw=true "Large Coffee")

References
=========================
[1] Alex Biryukov, Ivan Pustogarov, "Proof-of-Work as Anonymous Micropayment: Rewarding a Tor Relay", Financial Cryptography 2015, Puerto-Rico, USA.