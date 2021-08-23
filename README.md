install-script v.0.1-1.

======

Set your own software, this is basically a template that you can use, and install the software that I chose.

$ ./install-script

The script will get sudo on you, then will get the updated lists from apt repositories, then update and then set up your software. Fast and clean install for your system, respectively performs an update, upgrade, and lastly a dist-upgrade. After this is will perform an autoclean and an autoremove.

Currently the script will install the following software from the apt repositories: "linux-headers-uname -r python3-pip g++ htop neofetch terminator armitage npm etherape libreoffice bpytop fortunes virtualbox vlc sherlock gimp npm irssi"

Just copy your own Apt-get command in the place of the original one in the script.

Next the script will install Phoneinfoga with Curl. The script will move "phoneinfoga" to your /usr/bin directory so you can use it.

Then the script will add Fortunes to your ~/.bashrc to start when you launch a new Terminal application. Next the script will set your DNS server to 1.1.1.1 for Cloudflare.

Once the script is finished it will display a Fortune cookie for you.

m1bi --> chatblanche767 gmail com. (C)(2021) - All Rights Are Reserved.