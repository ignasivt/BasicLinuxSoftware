

# System Tools:
	* vim htop tmux git tilix curl iptraf-ng 
	* deja-dup
	* bpytop for terminal monitoring
	* echo "set -g mouse on" >> ~/.tmux.conf
	
## Browsers:
	apt install chromium / snap 

## Security:
	apt install ngrep ncat wireshark tshark tcpdump
		
## Media:
	apt install ffmpeg vlc gimp 
	gstreamer1.0-plugins-bad gstreamer1.0-plugins-ugly
	transmission-gtk
	pdftk 

## Other software
	apt install snapd
	samba smbclient 	
	telegram-desktop
	jq 
	snap install bitwarden spotify 
	
## Edit .bashrc
	force_color_promt=yes
	# Security aliases 
	alias rm='rm -i'
	alias cp='cp -i'
	alias mv='mv -i'		
 	Red prompt for root user
  	(In /root/.bashrc ->  PS1='${debian_chroot:+($debian_chroot)}\[\033[01;31m\]\u@\h\[\033[00m\]:\[\033[01;34m\]\w \$\[\033[00m\] ')


## Edit .vimrc
	" Disable mouse, we're using a GUI
	set mouse=
	set ttymouse=


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
	
