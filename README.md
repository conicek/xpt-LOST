xptminer-linux
==============

miner of metiscoin for ypool.net

HOW TO CLOUD MINE METISCOIN
Sign up for Digital Ocean 
Virtual Server : http://goo.gl/xIXumh
for 20 USD good server 
add 10 USD and 10 FREE
Use this code for $10 free credit: DIVEIN10
http://goo.gl/xIXumh  

sudo apt-get update

sudo apt-get install yasm -y git make g++ build-essential libminiupnpc-dev

sudo apt-get install -y libdb++-dev libgmp-dev libssl-dev dos2unix

sudo apt-get install -y libboost1.48-all libboost-chrono1.48-dev 

git clone https://github.com/conicek/xptminer-linux

cd xptminer-linux

make

./xpt -o http://ypool.net -u <username.worker> -p <password> -t 4
