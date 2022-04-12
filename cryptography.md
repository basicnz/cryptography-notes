# Message Authentication Code (MAC)
(Also known as a checksum)

## Why use a MAC
To protect the integrity and authenticity of a message.

## How it works
It creates an authentication tag of a message. MAC use symmetric keys to generate the authentication tag and verify it.
The MAC value protects a message's data integrity, as well as its authenticity, by allowing verifiers (who also possess the secret key) to detect any changes to the message content. 

MAC = Function 
m   = authenticaion tag
k   = key
x   = orginal message

m = MACk(x)

## Macs in secure communication
Secure communication systems often combine a cipher and the MAC for ___each network packet___.

## Protocols
IPsec
SSH
TLS

## To keep in mind
You cannot varify who has sent the message (No Non-Repudiation)

## Attacks on MAC

## Making MAC secure
### Secret-Prefix Construction (insecure)

## HMAC

### HMAC construction
#### ipad & opad stuff

## Summary

## MAC & Block Cipher

### CMAC

## MAC Designs
#### Some mac design example




