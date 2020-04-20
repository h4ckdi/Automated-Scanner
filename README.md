[![Follow on Twitter](https://img.shields.io/twitter/follow/phspades.svg?logo=twitter)](https://twitter.com/phspades)
[![Follow on Twitter](https://img.shields.io/twitter/follow/sumgr0.svg?logo=twitter)](https://twitter.com/sumgr0)
# Automated-Scanner

# We will rename the scanner into new one and we will update it that you can scan with a multiple domain in a txt file :D
# Stay Tune :D

Usage: `~$ bash scanner.sh example.com`

Running in background in VPS using nohup

Usage: `~$ nohup bash scanner.sh example.com &> example.out&`

----
**Subdomain Enumeration**
* [Amass](https://github.com/OWASP/Amass) 
* [Findomain](https://github.com/Edu4rdSHL/findomain)
* [Subfinder](https://github.com/subfinder/subfinder)
* [Assetfinder](https://github.com/tomnomnom/assetfinder)

* [Rapid7's Project Sonar](https://opendata.rapid7.com/sonar.fdns_v2/)
>https://github.com/phspade/Project_Sonar_R7
* [altdns](https://github.com/infosec-au/altdns)
>going back to altdns

**Scan All Alive Hosts with [filter-resolved](https://github.com/tomnomnom/hacks/tree/master/filter-resolved) and [Httprobe](https://github.com/tomnomnom/httprobe)**
>The reason we implement this, Is filter-resolved has an output which httprobe doesn't have. We filter it using diff and include it to vhost scan's wordlist :)

**Separating Cloudflare, Incapsula, Sucuri, and Akamai IPs from collected IPs**
>It's useless to scan Cloudflare, Incapsula, Sucuri, and Akamai IPs. *(Just like talking to a wall)*
>
>FYI, Install grepcidr first `apt-get install grepcidr`

**Subdomain TakeOver**
* [tko-subs](https://github.com/anshumanbh/tko-subs)
* [Subjack](https://github.com/haccer/subjack)

**Collecting Endpoints thru [Linkfinder](https://github.com/GerbenJavado/LinkFinder/)**

**Collecting Endpoints thru [Github](https://github.com/gwen001/github-search/blob/master/github-endpoints.py)**
>make sure to create `.tokens` file *(containing your github token)* together with `github-endpoints.py` *(probably in ~/tools folder)*.

**[HTTP Request Smuggler](https://github.com/gwen001/pentest-tools/blob/master/smuggler.py)**

**[ZDNS](https://github.com/zmap/zdns)**

**[Shodan](https://cli.shodan.io/)**

**[Aquatone](https://github.com/michenriksen/aquatone)**

**Port Scanning**
* NMAP
* [Masscan](https://github.com/robertdavidgraham/masscan)

**[Webanalyze](https://github.com/rverton/webanalyze) for Fingerprinting assets**

**~~[Default Credential](https://github.com/ztgrace/changeme) Scanning~~**
>Disable for now until further updates in this tool.

**File/Dir Discovery**
* [gau](https://github.com/lc/gau)
>gau combine with my [getching](https://github.com/phspade/getching) tool


**[Virtual Hosts](https://github.com/ffuf/ffuf) Scan**

* 401 Basic Authorization Bruteforce with FFUF
>Some subdomains has 401 authentication basic, so we need to bruteforce it with base64 credentials :)

* [DirSearch](https://github.com/maurosoria/dirsearch)

>Added **X-Forwarded-For Header** *(you should [setup your own dns server](https://medium.com/@spade.com/a-noob-guide-to-setup-your-own-oob-dns-server-870d9e05b54a))* to check for IP Spoofing Attack.

I hope that someone could help me to add more useful automated scanning technique :)

# Installation

For the installation of all the tools above. I linked all the github links, just make sure that its in the right directory PATH and your good to go. feel free to modify and feel free not to use it if you don't like it :)

# Future Tools to be added
* Install Script
>Thanks to [@sumgr0](https://twitter.com/sumgr0)

* Another Vhost Scanner
>Thinking about gobuster or codingo's VHost Scan

* HTML Report
>Just wait a little longer :D

**ALL CREDIT GOES TO AMAZING CREATORS OF THIS WONDERFUL TOOLS :)**

<sup>cannot make to mention y'all co'z i'm too lazy to do that though :D (i'm being honest here)</sup>

### Need a Digitalocean?

You can help me (slash) support me in this project by registering an account [here](https://m.do.co/c/9d633afb889b) *(with my referral code of course)* .

## Contributor

Big thanks to [@sumgr0](https://twitter.com/sumgr0) :)
