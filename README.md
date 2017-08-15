# Strongswan-role
Auto deploy StrongsWan IpSec on 2 node with Ansible( all run on Ubuntu 16.04 server). Step by Step:
  1. Update and setup packet strongswan
  2. tranfer Root Key and Root CA created by host master
  3. Create node key and node CA with Root key and root CA
  4. Config file strongswan.conf; ipsec.conf and ipsec.secerts
  5. Config firewalld

....Loading 
