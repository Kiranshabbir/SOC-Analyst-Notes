# Day 10 - TCP , UDP and the three way handshake 
  Date: Nov 5, 2026


## 1. What I learned
- UDP is fast, connectionless, unreliable network protocol.
- TCP is slow, reliable, ordered, error checked data delivery.
- Three way handshake is the client asks to connect(SYN),the server agrees and asks to connect back (SYN-ACK)and the client confirms(ACK).


## 2. What I did
- I watched: Introduction to IP - CompTIA Network+ N10-009 - 1.4, and read the handshake article.
- I drew the three-way handshake (PC1 and PC2) and a TCP vs UDP table.
- Phone call analogy: SYN = you dial, SYN-ACK = they pick up and say "Hello?", ACK = you reply "Hi, it's me" — then you talk.
- I finished TryHackMe: Junior Security Analyst Intro and Linux Fundamentals (Pt1).


## 3. New words
- TCP= transmission control protocol 
- UDP= user datagram protocol 


## 4. What was hard
- Nothing was hard.

## 5. Explain in 2 sentences
- TCP checks that data arrives, so it is reliable but slower, and UDP does not check, so it is faster. Before sending data, TCP starts a connection with SYN, SYN-ACK, and ACK.
