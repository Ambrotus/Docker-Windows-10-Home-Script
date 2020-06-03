# Docker-Windows-10-Home-Script
The Hyper-V Components script from The Docker forums
Installation Tutorial
https://www.youtube.com/watch?v=ti2-2E3PFLs&lc=UgwQRq3pV0qXPBVNlRl4AaABAg

While microsoft says Windows 10 Home edition does not support Hyper-V and that Pro does.
We can install it to windows 10 home by installing the hyper V components via a batch file and editing 2 registry keys 
to fake the docker windows check when it installs by making it think we have pro.


Create hyperVComponents.Bat and hyperVContainers.Bat

Running the following *.bat scripts as Admin that will install the Hyper-V components (reboot required)
and the container features

Thanks to all the people here that put all the info in one area.
Source: https://forums.docker.com/t/installing-docker-on-windows-10-home/11722/28
my old pastebin link - https://pastebin.com/nTmZiJVe
