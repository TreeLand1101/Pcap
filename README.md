# Network-Programming-HW3
# Pcap
````
git clone https://github.com/TreeLand1101/Pcap
cd Pcap
make
sudo -s
./pcap_checker [-f filename] [-o dumpfile] [-p protocol]
````
- 那個封包擷取的時間戳記
- 來源MAC位址、目的MAC位址、Ethernet type欄位
- 如果那個封包是IP封包，則再多顯示來源IP位址與目的地IP位址
- 如果那個封包是TCP或UDP封包，則再多顯示來源port號碼與目的port號碼

bonus
- support variety of devices
- support pcap_open_live
- pcap dumper
- protocol filter
