# Burp suite private collaborator
A script for installing private Burp Collaborator with Let's Encrypt SSL-certificate.
Should work on (Ubuntu 18.04):
- Amazon AWS EC2 VM with or without Elastic IP.
- Microsoft Azure VM
- DigitalOcean VM with or without Floating IP.
- Any other platform as long as the VM has public IP.

Please see [this blog post](https://teamrot.fi/2019/05/23/self-hosted-burp-collaborator-with-custom-domain/) for usage instructions.

## TL;DR:

1. Clone this repository.
2. Install Burp to /opt/BurpSuitePro.
3. Run `sudo ./install.sh yourdomain.fi`.
4. You should now have Let's encrypt certificate for the domain and a private burp collaborator properly set up.
5. Start the collaborator with `sudo service burpcollaborator start`.
6. Configure your Burp Suite Professional to use it.
7. ????
8. Profit.
