
# Warnings.  

I TAKE NO RESPONSIBILITY FOR THE THIS.  YOU ARE USING IT AT YOUR OWN
RISK.  I SAY THIS BECAUSE I AM NOT PRETENDING TO KNOW WHAT "MAINTAINERS"
USE TO DOUBLE CHECK / SAFTEY CHECK THE PRODUCTION OF A DEB FILE

I have NO idea how the "maintainers" actually create thier releases.

I examine a recent .DEB file and then worked to find out what I thought
needed to be put into one.  I am at this stage shamlessly copying things
because that is what was in the maintainers deb.  I should really 
quetion every man file, etc.

This is going to be imperfect.

The thinking is that many of the maintainers for the repositories
are sometimes going to have to change the code for thier distro.
For example:  OpenSSH is developed for NetBSD.

The "control" file here is generic as all get out

# Purpose

This is being used to learn more about creating a deb file for a larger scale project.  Plus sometimes its awkward to find a deb file for new versions of projects.  Also the source for a project most likely won't contain code to create an archive.

# Getting this

git clone https://github.com/tlh45342/create-bash-deb.git



This script is designed to create a DEB file based on a fresh
compile / install of the bash.

Please note that the default I used had the bash file in /usr/local/bin/bash
The default instance generated uses /usr/bin/bash
So I have attempted to correct for this.
