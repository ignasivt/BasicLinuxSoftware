

# System Tools:
	* vim htop tmux git tilix curl iptraf-ng 
	* deja-dup
	* bmon for terminal network usage 
	
## Browsers:
	apt install chromium / snap 

## Security:
	apt install ngrep ncat wireshark tshark tcpdump

		
## Media:
	ffmpeg vlc gimp 
	gstreamer1.0-plugins-bad gstreamer1.0-plugins-ugly
	transmission-gtk
	pdftk 

## Other software
	apt install snapd
	snap install bitwarden spotify skype
		disable skype share anything gnome action: rm /var/lib/snapd/desktop/applications/skype_skypeforlinux-share.desktop
	apt install samba smbclient 	
	apt install telegram-desktop
	apt install jq 
	snap install discord 

## Edit .bashrc
	force_color_promt=yes
	some more grep color aliases 
	alias rm='rm -i'
	alias cp='cp -i'
	alias mv='mv -i'		

## Sublime
	wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
	echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
	update & install sublime

## Set aggressive sleep for NAS devices:
	hdparm -B 24 -S 24 /dev/sda

## Setup deja-dup
	From nautilus browse to smb://server/resource_name, save credentials forever
	Run deja-dup and set the folder to smb://server/resource_name/deja-dup-folder

## VMs
	libvirt-clients virt-manager
	
