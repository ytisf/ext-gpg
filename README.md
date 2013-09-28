ext-gpg
=======

An extreme version of GnuPGP able to create keys of up to 16kb. 

So, as you most hackers love your privacy, and even if you are not a hacker, we still LOVE those big GPG keys. Only issue is that today, computers are growing stronger and stronger. In the GnuPG package, hardcoded is a limit of 4096-bit key generation. Ergo you cannot create a key bigger than 4,096-bit. So, we took the source of that nice ol’ GnuPG 1.4.12 and modified it to hard code a top limit of 16,384-bit key generation. Any program can handle the understanding of this but not generate.

You'll need to have these libraries so that compilation will be successful.

sudo apt-get install libgcrypt11-dev libgpg-error-dev libassuan-dev libksba-dev subversion automake checkinstall

