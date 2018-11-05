# Honeypot-Hosted-on-AWS
I deployed a Dionaea Honeypot on an Ubuntu 14.04 distro hosted on an Amazon EC2 instance.

The only issue that I encountered was translating all the intstructions that were meant for GCP to AWS.

In the past hour, there were approximately 200 attacks, with most of the attacks originating from China.
The top attacker's IP address is 120.27.4.81 (China) with 108 attacks.
The top port that was attacked was port 80 (114 times).

I also deployed a Amun on a separate EC2 instance.
It appears that this honeypot is attacked at a much lower frequency compared to that of the Dionaea Honeypot.

At one point I was locked out of my AWS because it appeared that the private key pair was changed
![lockedout.png]()
