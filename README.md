


**Nicole**
=========


![Nicole](https://cdn.pbrd.co/images/GKWZujX.png)


-----


<ul>
<li><a href="#nicole">Nicole</a><ul>
<li><a href="#wallet-download-github">Wallet Download Github</a></li>
</ul>
</li>
<li><a href="#nicole-vital-statistics">Nicole Vital Statistics</a></li>
<li><a href="#who-is-nicole">Who is Nicole?</a><ul>
<li><a href="#nicoleconf">Nicole.conf</a></li>
<li><a href="#compiling-nicole-qt4-dependencies">Compiling Nicole QT4 Dependencies</a></li>
<li><a href="#nicolexplorer">Nicolexplorer</a></li>
<li><a href="#genesis-and-tx-hash">Genesis and TX Hash</a></li>
</ul>
</li>
</ul>



-----





**Nicole is a daring new cryptocurrency based on purely on Proof-of-Stake.**


**There are no POW blocks left to mine.**


-----



Wallet Download Github
-------------


[Download Nicole-qt](https://github.com/NicoleDev/Nicole-qt/blob/master/Nicole-Dev.zip)

-----

Nicole Vital Statistics
=======================



Item        |  Spec     |
 --------  |  --------  
Coin:         |  Nicole    |  
Ticker:       |  NICOLE    | 
Algorithm:       |  sha256d    |
Reward Type:       |  POS    |  
Staking Confirmations:       |  15    | 
RPC:       |  6526    | 
P2P:       |  6527    |
POS Reward:       |  100%    | 
Minimum Staking:       |  1 minute    | 
Maximum:       |  Unlimited    | 






-----


Who is Nicole?
==============



This is Nicole



![Nicole bkg.png](https://cdn.pbrd.co/images/GKX74R4.png)


-----



Nicole.conf
--------------------

    rpcuser=Nicolerpc
    rpcpassword=somethinglongwithdifferentcharacters
    rpcallowip=127.0.0.1
    daemon=1
    server=1
    rpcport=6526

-----


Compiling Nicole **QT4 Dependencies**
--------------------

**Daemon | Nicoled**

*NB: Do not forget to "strip Nicoled"*



    $ git clone https://github.com/NicoleDev/Nicole.git
    $ sudo apt-get update
    $ cd Nicole/src
    $ make -f makefile.unix USE_UPNP=1
    $ strip Nicoled
    $ ./Nicoled




-----


Nicolexplorer
--------------------


[Nicolexplorer](http://explorer.nicole-lovely.info:3001)


-----

Genesis and TX Hash
-------------


- Merkle Root: d92f371c9eb3838534574ee914b14c27ce7358bc634966385b5f91ef29b68998


- Genesis Block: 000000dac84ae40c0611c87237aa87bbe38c4cc25566d3c7af7983b064d6295e
