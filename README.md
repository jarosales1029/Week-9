# Week-9
Honeypots

Deployed 3 honeypots (mhn-honeypot-1, mhn-honeypot-2, and mhn-honeypot-3) through GCPN.

Some issues I encountered included, downloading the JSON files.  I couldn't seem to get the correct permissions to implement the commands correctly through cmd/ssh.  This was remedied by electing the SSH option from within the GCPN web browser.

There were over 10,000 attacks collectively recorded.  Several different IP addresses from different countries.  

My attacks included NMAP calls to see which ports were exploitable.  After going back in, I brought mhn-honeypot-1 down and mhn-honeypot-2/3 up.  I downloaded two json files.  When I was running just 1 honeypot (mhn-honeypot-1) the json file is titled session.json and the 2nd json file is with mhn-honeypot-2 and 3 titled as session1.json. 
