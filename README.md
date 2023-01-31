# Tron-multisig-sweep
------------------

Please star the repo so I can update the sweeper

How to setup
--------------------

* Open the Config.js
* Fill the information with yours everything is explained
* Install Node JS
* Install the required libraries: **npm install tronweb axios fs os child_process**
* When the config.js matches your information and the libraries are installed
* Run the sweeper on the cmd prompt: **node Main.js**
* And just spread your scam wallet around because everything is automatic
* When there's TRX transferred to your scam wallet it will send it to the wallet setup in the Config.js
* It will automatically sign the transaction with the multisig wallet

Additional information
-----------------------------

* Make sure that you activated the multisig on the wallet that owns the scam wallet by paying the fee which is 100 TRX.

Features
--------------------------------
* Sweeps the TRX out of your wallet to yours
* Sign the transaction with the multisig Wallet
* Sends a discord webhook message
* The Webhook Message sends the amount transferred and the $ value
