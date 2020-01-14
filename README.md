# pcap
A small collection of network traffic packet captures

## CVE-2019-19781
Added on 2020-01-14 to host PCAP referenced in the ["Rough Patch: I Promise It'll Be 200 OK"](https://www.fireeye.com/blog/products-and-services/2020/01/rough-patch-promise-it-will-be-200-ok.html) blog:
* [First PCAP file](https://github.com/itsreallynick/pcap/raw/master/cve-2019-19781/cve-2019-19781_port80_GET_vulnerability_path_check.pcap) - GET request for exploit scanning - checking .conf file for a 200 OK response
* [Second PCAP file](https://github.com/itsreallynick/pcap/raw/master/cve-2019-19781/cve-2019-19781_port80_POST_trustedsec_exploit.pcap) - POST request exploiting the vulnerability using [TrustedSec's](https://github.com/trustedsec/cve-2019-19781) publicly-available tool
* Blog: https://www.fireeye.com/blog/products-and-services/2020/01/rough-patch-promise-it-will-be-200-ok.html

---
Your pal, [@itsreallynick](https://twitter.com/ItsReallyNick)
