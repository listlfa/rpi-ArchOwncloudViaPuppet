rpi-ArchOwncloudViaDockerAndPuppet
==================================

Arch Linux runng Owncloud on the RaspberryPi, contained within Docker, managed by Puppet. Includes storage to external USB.

These are my instructions for my environment; I recommend you read through everything once and note where your environment is different first, before you attemp to do anything.

- Warnings
- Notes
- Assumptions
- Outcomes
- Steps
- 	Prepare your SD card for the Pi
- 	Setup Arch
- 	Setup Puppet
- 	Get the Config setup
- 	Apply Config to the Pi
- 	Enjoy


- Warnings
-
Per the notes I am a beginner and this is for my environment.

Therefore this only installs
- Owncloud 7
- Nginx

And you are required to configure the
- Domain name
- SSL Key
- SSL Passphrase
- 
- 
- - Notes
- 
I am a beginner for Linux.  Currently these are my notes for my enviornment some/all of this may not suit you.

Some system linux commands  http://www.tecmint.com/command-line-tools-to-monitor-linux-performance/

- Assumptions
-
- ASDL or faster internet
-	Have seen and used at least once a command line interface like DOS (Windows) or Bash (Linux)
-	PC or laptop running Windows
- Raspberry Pi B or Raspberry Pi B+
	- Australian store; http://www.element14.com/community/community/raspberry-pi
- SD Card (4GB or more)
- USB Drive.  One with a power cord recommended, not those little ones with only a USB cable. I use 2GB.

- Outcomes
-
- Have Owncloud 7 automatically installed and configured
- 	Following manual
- 		Install of linux
- 		Configure minimal Owncloud settings (via text file)
