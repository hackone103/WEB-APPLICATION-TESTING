# Dns Reconnaissance
# DNS (Domain Name Server)
  - The doamin name systems (DNS) is a names resolution service. DNS resolves human-friendly address
    (such as www.targt.com) info IP address (such as 192.168.1.1).

# Types of DNS Servers
  + Authoritative DNS Servers
     - Master(Primary)
     - Slave (Secondary)
  + Caching/Rescursive DNS Server

#  Authoritative DNS Servers
   + Master(Primary)
   > DNS Record
      
# Domain To Conver address

# NSlookup
  - nslookup <domain.com>
  - nslookup -type=AAAA <domain.com>        \\    Check AAAA Record
  - nslookup -type=NS <domain.com>          \\    Check NameServer Record
  - nslookup -type=MX <domain.com>          \\    Check MailServer record
  - nslookup -type=NS <domain.com> <ns.server.com>      \\    Website NameServer Resolve
  
# dig 
  - dig <target.com> 
  - dig <target.com> ANY                    \\ Check ANY Record
 
# Host
  - host <targe.com>
  - host -t any <target.ocm>

# Online Websites
  - google Public dns
  - G suite toolbox dig
  - ViewDNS.info
  - Central OPs.net

# Check IP Same Netork 
  - IpLocation.net   


  


