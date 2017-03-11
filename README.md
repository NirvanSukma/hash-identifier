
hash-identifier
MARCH 11, 2017 portsPassword Attacks	
hash-identifier Package Description

Software to identify the different types of hashes used to encrypt data and especially passwords.

Source: http://code.google.com/p/hash-identifier/
hash-identifier Homepage | Kali hash-identifier Repo

    Author: MRX_001
    License: GPLv3

Tools included in the hash-identifier package
hash-identifier – Identify different types of hashes

Identify the different types of hashes.
hash-identifier Usage Example
root@cyrus-os:~ # python HashID.py
   
############################################################################# 
#                                                                           #
#                             CYRUSTOOL                                     #
#                         HASH IDENTIFIER                                   #
#                     Welcome and dont disclaimer                           #
#                       Author By -Nirvan Sukma-                            #
#                                                                           #
#  contact me in nirvansukma1998@gmail.com or http://nearvanskm.16mb.com/   #
#    TEAM Penetration From Indonesia : http://www.cyruscyberid.tk/          # 
#                                                                           #
#                                                                           #
#############################################################################

   -------------------------------------------------------------------------
 HASH: 098f6bcd4621d373cade4e832627b4f6

Possible Hashs:
[+]  MD5
[+]  Domain Cached Credentials - MD4(MD4(($pass)).(strtolower($username)))

Least Possible Hashs:
[+]  RAdmin v2.x
[+]  NTLM
[+]  MD4
[+]  MD2
[+]  MD5(HMAC)
[+]  MD4(HMAC)
[+]  MD2(HMAC)
[+]  MD5(HMAC(Wordpress))
[+]  Haval-128
[+]  Haval-128(HMAC)
[+]  RipeMD-128
[+]  RipeMD-128(HMAC)
[+]  SNEFRU-128
[+]  SNEFRU-128(HMAC)
[+]  Tiger-128
[+]  Tiger-128(HMAC)
[+]  md5($pass.$salt)
[+]  md5($salt.$pass)
[+]  md5($salt.$pass.$salt)
[+]  md5($salt.$pass.$username)
[+]  md5($salt.md5($pass))
[+]  md5($salt.md5($pass))
[+]  md5($salt.md5($pass.$salt))
[+]  md5($salt.md5($pass.$salt))
[+]  md5($salt.md5($salt.$pass))
[+]  md5($salt.md5(md5($pass).$salt))
[+]  md5($username.0.$pass)
[+]  md5($username.LF.$pass)
[+]  md5($username.md5($pass).$salt)
[+]  md5(md5($pass))
[+]  md5(md5($pass).$salt)
[+]  md5(md5($pass).md5($salt))
[+]  md5(md5($salt).$pass)
[+]  md5(md5($salt).md5($pass))
[+]  md5(md5($username.$pass).$salt)
[+]  md5(md5(md5($pass)))
[+]  md5(md5(md5(md5($pass))))
[+]  md5(md5(md5(md5(md5($pass)))))
[+]  md5(sha1($pass))
[+]  md5(sha1(md5($pass)))
[+]  md5(sha1(md5(sha1($pass))))
[+]  md5(strtoupper(md5($pass)))

   -------------------------------------------------------------------------

   -------------------------------------------------------------------------
Tags: passwords	
