# SpoofThatMail
Bash script to check if a domain or list of domains can be spoofed based in DMARC records


File with domains:
```
sh SpoofThatMail.sh -f domains.txt
```
One single domain:
```
sh SpoofThatMail.sh -d domain
```
![alt text](https://i.imgur.com/8exMAAs.png)


The script may not work if sp param is before p param (currently working on this)

Test manually using nslookup -type=txt _dmarc.domain.com
