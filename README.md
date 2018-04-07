# CS9
Pooh Bear loves these things =D
## 1. Which Honeypot(s) you deployed
I only deployed the required Ubuntu - Dionaea with HTTP honeypot.
## 2. Any issues you encountered
The writeup on the instructions website very bad. I spent more time on google searches trying to figure out what the instructions wanted me to do since the instructions seem to think you already know how to run the program. Next time I recommend including screenshots of every step. I had to install the Google Cloud SDK via interactive installer since the standard installer was giving me issues. Another example of this is TCP port 80 wasn't opened, which caused me unnecessary frustration as I kept on backtracking to see what I did wrong, only to realize that the instructions were deficient.
## 3. A summary of the data collected: number of attacks, number of malware samples, etc.
As of 9 APR 2018 19:51 PT, I had 4,347 attacks on my honeypot, but interestinly no malware samples. I suspect that I can collect more if I let the honeypot run longer.

The most interesting thing I found was within minutes of deploying the honeypot, I had over a thousand hits. Keep in mind this was a random IP address that was just created and didn't have actionable data on it, as opposed to big corporate sites that log many more pings and attacks. MHN Server will tell you which country the source IP came from, saving time from having to manually look up IP addresses to figure out where it is coming from. The usual suspects were there such as Russia and China, which is interesting since there might be reverse psychology of attackers spoofing their IP to those countries for attacks, or it may just be attackers that don't give a crap about masking their location.
## 4. Any unresolved questions raised by the data collected
None at this point
