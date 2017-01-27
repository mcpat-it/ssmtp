# ssmtp
patched ssmtp based on ssmtp 2.64

# sSMTP - Simple SMTP
sSMTP is a simple MTA to deliver mail from a computer to a mail hub (SMTP server). sSMTP is simple and lightweight, there are no daemons or anything hogging up CPU; Just sSMTP. Unlike Exim4, sSMTP does not receive mail, expand aliases, or manage a queue.

# Setting up sSMTP
sSMTP's main configuration file is located at ssmtp.conf 

# Using sSMTP with Gmail
Using sSMTP with Gmail is simple, you just have to change a few options around and add in TLS encryption and change Google's server to port 587

# Patches
with DEBIAN patches and mcpat patches
 *TLS patch (made by mcpat)
 *Libcrypto patch (made by mcpat)
 *557741-remote-addr.patch
 *508759-garbage.patch
 *LDFLAGS.patch
 *bug584162-fix.patch
 
 # Tested and working
 compiled with GCC 5.3.0 on a dreambox DM900 (armv7)
