# cryptonote-wallet

Dependencies
with out boost and wind 
sudo apt-get install build-essential cmake pkg-config libssl-dev libzmq3-dev libunbound-dev libsodium-dev libminiupnpc-dev liblzma-dev libreadline6-dev libldns-dev libexpat1-dev libgtest-dev doxygen graphviz

with wind 
sudo apt-get install build-essential cmake pkg-config libssl-dev libzmq3-dev libunbound-dev libsodium-dev libminiupnpc-dev libunwind8-dev liblzma-dev libreadline6-dev libldns-dev libexpat1-dev libgtest-dev doxygen graphviz


then 
 
 boost 1.62.0 bc i found that it works with openssl 1.1
 
 
wget  https://sourceforge.net/projects/boost/files/boost/1.62.0/boost_1_62_0.tar.bz2
tar xvfo boost_1_62_0.tar.bz2
cd boost_1_62_0  
./bootstrap.sh
sudo ./b2  
