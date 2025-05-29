# Lesson 1:

- `tshark -h`: help  
- `tshark -D`: list available sniffing interfaces  
- `tshark -v`: version info  
- `tshark -i interfacename/number`: choose interface (or specify number)  
- `tshark`: no parameter (sniff traffic like tcpdump)  
- `tshark -r pcapname`: read  
- `tshark -c 10`: stop capturing after 10 packets  
- `tshark -w file.pcap`: write capture to file.pcap  
- `tshark -V`: verbose  
- `tshark -q`: silent mode  
- `tshark -x`: show packet bytes  
- `-a`: capture conditions for single loop (duration: x or filesize:x where x = integer)  
- `-b`: capture condition for multiple loops  
- `-f`: capture filter (host|net|portrange x-x where x = integer)  
- `-Y`: display filter (ip.addr/ip.src/ip.dst, tcp/tcp.port/tcp.srcport/tcp.dstport, http/http.response.code == x, dns/dns.qry.type == x)  
