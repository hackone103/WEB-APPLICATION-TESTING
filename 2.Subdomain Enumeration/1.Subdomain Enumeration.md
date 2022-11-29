# Subdomain Enumeration

  Subdomain enumeration is the process of finding valid subdomains for a domain, but why do we do this? We do this to expand our attack surface to try and discover more potential points of vulnerability.

#### Google Dorks 
`site:<target.com>`

#### Third party services
  1. VirusTotal : <a href="https://www.virustotal.com/gui/home/url">Click</a>

#### SSL Certificates
  1. crt.sh :  <a href="https://crt.sh/">Crt.sh</a>
  ```
  # crtsh.py
  python3 crtsh.py -t targe.com
  ```
## 1. Subdomain Enumeration
#### Amass
##### Basic command to enumerate the target:
  ```
  # Find ASN ID’s through Organisation name
  amass intel -org ‘Org Name’  

  # Search based on ASN                    
  amass intel -asn <ASN ID’s>  

  # Passive Recon                  
  amass enum -passive -d <URL> -src  

 # Find SB Domain and Ip
  amass enum -src -ip -d <domian.io>

  # Amass output Filters Commands (IP AND SUBDOMAIN)
  cat <Amass-Output.txt> | cut -d ']' -f 2 | awk '{print$1}' | sort -u >> <Save-F-Output.txt>
```
#### Assetfinder
```
  assetfinder -subs-only domain.com | tee output.txt 
```
#### Subfinder
#### Find subdomains of a target domain
```
subfinder -d domain.com | tee output.txt
```
#### Sublist3r
####  Fast subdomains enumeration tool for penetration testers
```
 sublist3r -d facebook.com | tee output.txt
```
## 2.DNS Subdomain resolvers (Check active SubDomain)
#### Massdns
```
massdns -r <dns-resolvers.txt> -o S -w <output_file.txt> <domian.file.txt>

# Massdns output filter
 cat <massdns_Output_file.txt> | awk '{print$1}' | sed 's/.$//' | sort -u >> <output.file.txt>
```
#### Shuffledns
```
shuffledns -d taget.com -list targe-domin.txt -r resolvers.txt -o shuffledns-output.txt

```
## 3.Subdomain Bruteforcing
#### shuffledns
```
shuffledns -d domain.com -w wordlist.txt -r resolver.txt -o output.txt
```
#### knockpy 
```
knockpy domain.com -w wordlist.txt
```
#### ffuf 
```
wfuzz -c -f sub-fighter -w wordlist.com -u 'https://target.com' -H "Host: FUZZ.target.com" 
```
#### gobuster 
```
gobuster dns -d targe.com -t 50 -w wordlist.txt
```

# 4.Port Scanning
### Naabu 
#### A fast port scanner written in go with focus on reliability and simplicity.
```
naabu -p 80,443,21-23 -l sub-Doamin.txt
```

# 5.Screenshots
### Aquatone
```
cat domain.txt  | aquatone -resolution -out src

```
# 6.Domain Convert HTTP and HTTPS
#### httprobe
```
cat subfinder.txt | httprobe
```

# 7.Links
#### waybackurls
```
cat subfinder.txt | waybackurls
```
Burp : <a href=""> BurpJSLinkFinder </a>- Burp Extension for a passive scanning JS files for endpoint links.
LinkDumper
#### Gau
```
 cat example.com | gau
 cat domains.txt | gau --threads 5
 gau example.com google.com
 gau --o example-urls.txt example.com
 gau --blacklist png,jpg,gif example.com
```

# 8. Fuzzing
#### dirsearch
```
dirsearch -u https://<domian.com>
```
#### ffuf
```
ffuf -u targe.com -w wordlist.txt
ffuf -c -w  <wordlist.txt> -u https://<domian.com>/FUZZ
``` 
#### wffuf 
```
wffuf -w <wordlist.txt> https://<domian.com>/FUZZ
```