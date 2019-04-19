###  ZEON  Panda 

Options used to compile and link:

  with wallet   = yes
  
  with gui / qt = no
  
  with zmq      = yes
  
  with test     = no
  
  with upnp     = no
  
  debug enabled = no
  
On ubuntu 18.04

sudo apt-get install libssl1.0-dev

./configure --without-miniupnpc  --enable-hardening  --without-gui


