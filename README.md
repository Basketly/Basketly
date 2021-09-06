# Basketly 🧺

Your house is burning down.  You can escape with 3 possesions.  Is one of them a collection of important files (eg. digital photos)?  Better keep those files safe and not store them all in one basket...

## What is Basketly?
Basketly is an app that lets you backup your files on your friends' computers and vice-versa.  It takes advantage of extra disk space you might have that is not very useful for backing up files on the same disk.  All files are encrypted so nobody can see your files besides you.

**What happens if a peer goes offline? Can I still access my files?**
> All files are sharded using Reed-Solomon erasure coding.  This means as long as 50% of the peers are online you will be able to access your files.

**Is Basketly free?**
> Basktely is free for non-commercial use

**Can other peers view my files?** 
> No, all files in Basketly are encrypted with your password using modern encryption (specifically RFC 7539 https://tools.ietf.org/html/rfc7539)

## Getting Started
Basketly is in very early stages and currently runs on Windows and Linux.
1. Download latest executable from release page
1. Setup simple playground with `$ bkt --playground 2`
1. See help for more info and commands `$ bkt --help`


## Roadmap
Roughly ordered highest prio first
1. Global peer discovery
1. GUI
1. Mac support
1. Versioning
1. STUN
1.

