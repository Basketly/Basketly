# Basketly 🧺
## What is Basketly
Basketly is a distributed file backup system.  It allows one Basktely peer to encrypt and spread files across many other Basketly peers.  The idea is that a group of friends can all use Basketly to backup eachother's files.
### Can other peers view my files?
No.  All files in Basketly are encrypted with your password using modern encryption (specifically RFC 7539 https://tools.ietf.org/html/rfc7539)
### What happens if a peer goes offline?  Can I still access my files?
All files are sharded using Reed-Solomon erasure coding.  This means as long os 50% of the peers are online you will be able to access your files.
### Is Basketly free?
Basktely is free for non-commercial use.

# Getting Started
Basketly is in very early stages and currently partly works on Windows and Linux.
1. Download latest executable from release page
1. Setup simple playground with `$ sib --playground 2`
1. See help for more info and commands `$ sib --help`


# Roadmap
1. GUI
1. Global peer discovery
1. Mac
1.

