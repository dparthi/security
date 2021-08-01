

[TOC]

# Hardening Your Brand New VPS System

- Ubuntu 20.04
- SSD Nodes VPS (12c, 48GB, 600GB VM)

So, I was setting up my new VPS server as a digital playground and as usual I started with the "how to harden my vps server" question thrown at Google. One interesting (and must be a straightforward & painless) option that showed up was to use Ubuntu Advantage Subscription (free for personal use as of this writing), which will provide the CIS hardening tools. I did not want to go down that path (who doesnt love a little pain?) so, decided to do my "hands-on" hardening.

## Reference Links

Below are the links that helped me:

> https://www.informaticar.net/security-hardening-ubuntu-20-04/

The above one is crisp and on dot. In about 10 minutes, I had secured the system - NO root login, NO password login, MFA (with Google authenticator) and a simple IDS to boot. There may be a small glitch when it comes to passwordless + MFA login. Below link saves you:

> https://serverfault.com/questions/783082/how-to-use-the-ssh-server-with-pam-but-disallow-password-auth

