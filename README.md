This project proposes the implementation of a blockchain-based tracking system tailored for outbound shipments within a packaging company. The conventional logistics processes in the packaging industry often encounter challenges such as lack of transparency, inefficiencies in tracking, and susceptibility to errors or fraud. Leveraging blockchain technology offers promising solutions to address these issues by providing a decentralized, immutable ledger for recording and verifying shipment data

how to run in loval machine
This document will help you understand how you can test this decentralized application on your own computer.
But please not, I made this project open source just so that other people can add something upon this existing setup or for educational purposes.
This project is not supposed to be copied and used for your semester projects or commercial purposes.

INSTRUCTIONS-
1) Download and install Ganache (https://www.trufflesuite.com/ganache)
2) Download and install Xampserver on windows (https://www.apachefriends.org/download.html) or MAMP on MacOS X (https://www.mamp.info/en/windows/)
3) Download and install Google Chrome (in case you don't have it already). Go to Chrome store and download Metamask (https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn)
4) Create a metamask account.
5) Run Ganache.
6) In metamask, select Networks > Custom RPC
7) Give any name to network.
8) Copy RPC Server URL from Ganache (It should probably be HTTP://127.0.0.1:7545 but please check)
9) Go to Metamask > Accounts > Import Account.
10) Open Ganache, go to Accounts tab, click on the key icon on the right side for any account and copy the private key.
11) Paste this key in Metamask import account section.
12) Copy the smartcontract.sol from this repo and paste it in https://remix.ethereum.org/ code section.
13) Save it, go to compile tab and compile the code.
14) Go to deploy tab, select Environment as 'Injected Web3'
15) Click deploy.
16) Copy the contract address and paste it in app.js file.
17) Copy the contract ABI from compile tab and paste it in app.js file.
18) Start MAMP or Xampserver (Whichever you installed)
19) Paste the project folder inside htdocs folder of the root directory.
20) Go to localhost or localhost:8888/  (This URL may change depending on the software you installed and your OS)
21) Open phpmyadmin, go to SQL and paste the sql queries provided inside the sql folder.
22) Execute the queries.
23) Open URL http://localhost:8888/SupplyChainDAPP_FULL or http://localhost/SupplyChainDAPP_FULL (This URL may change depending on the software you installed, your OS, and project name)
24) It should be running as expected.
#   B L O C K C H A I N _ P E S 2 U G 2 1 C S 2 3 7 _ 2 2 8 _ 8 1 2  
 