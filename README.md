mailIP
======

A script that will send the host's IP adress via email when network is up.
Tested on debian server with DHCP.

Much cred to this answer on stack overflow: http://stackoverflow.com/a/6119043

## What you need
*ssmtp. I use it with Gmail. This guide worked well for me: http://www.nixtutor.com/linux/send-mail-with-gmail-and-ssmtp/

## How to install (on debian)
*put the script in /etc/network/if-up.d/ with 'sudo mv mailIP /etc/network/if-up.d/'
*make it executable with 'sudo chmod +x /etc/network/if-up.d/mailIP'

