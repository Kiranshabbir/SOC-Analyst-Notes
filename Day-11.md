# Day 11 - DNS and nslookup
  Date: Nov 6, 2026

## 1. What I learned
- DNS changes a website name like google.com into an IP address.
- nslookup is a command that asks a DNS server for the IP of a name.
- A name can have an IPv6 address and an IPv4 address.

## 2. What I did
- I reviewed my DNS in Detail notes and watched: Nslookup and Dig - CompTIA Network+ N10-005 - 4.3
- I opened Command Prompt and ran: nslookup google.com and nslookup youtube.com
- DNS server I used: 192.168.1.1 (my home router)
- google.com: IPv4 142.250.201.110, IPv6 2a00:1450:4019:819::200e
- youtube.com: IPv4 142.250.202.142, IPv6 2a00:1450:4019:815::200e
- The line "Server: UnKnown" means nslookup could not find a name for my DNS server IP. This is normal at home.
- "Non-authoritative answer" means the answer came from my DNS server's memory (cache), not from Google's own server.
- I finished the TryHackMe rooms: SOC Role in Blue Team and Search Skills.

## 3. New words
- DNS = Domain Name System
- Domain name: the name of a website, like google.com.
- nslookup: a command to look up a domain's IP address.
- Non-authoritative answer: an answer from a cache, not from the owner's server.

## 4. What was hard
- Nothing was hard

## 5. Explain in 2 sentences
- DNS is like a phone directory that turns a name like google.com into an IP address. nslookup is the command that asks DNS for that IP.
