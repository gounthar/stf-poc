PoC for STF deployment on a Raspberry Pi 3B+
===========
# Installation

* install [Hypriot]
* clone this repo

# Usage
choose an IP your deployment should use, usually that will be the IP of your host.  
choose a secret to be used for inter-service authentication.  
Update the `.env` file accordingly

Run `docker-compose up -d --build` and `docker-compose logs -f &` to get some feedback on what's going on.
Point your browser to the IP you chose,  
login by providing any username and valid e-mail.


A little write-up on this setup:  
https://medium.com/@nikosch86/getting-started-with-automated-in-house-testing-on-android-smartphones-using-stf-dafecee4a8ee  
If you clap it will make me happy :)

[Hypriot]:https://blog.hypriot.com/downloads/
