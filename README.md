 ## Overview
 [10fastfingers](https://10fastfingers.com/) clone for desktop
 
 ## Download
 Download windows or linux [release](https://github.com/DarkShadowFT/TypingTestApp/releases/)

 ## Install
 
 #### Windows
 This should work out of the box but if you get DLL errors, download [VC packages]( https://getintopc.com/softwares/utilities/visual-c-plus-plus-redistributable-packages-free-download-1557309/)

 #### Linux
 You need **SFML** and **TGUI**.

 ##### TGUI
 Download this [file](https://github.com/texus/TGUI/archive/v0.8.8.zip)  
 Unzip it and cd to where you extracted the zip  
 Run these commands  
 `cmake -DCMAKE_INSTALL_PREFIX=/usr . \-DCMAKE_BUILD_WITH_INSTALL_RPATH=TRUE`  
 `make`  
 `sudo make install`
 
 
 ##### SFML
 ###### Arch Linux, Manjaro and other [Arch-based distros](https://wiki.archlinux.org/index.php/Arch-based_distributions)
 
 `sudo pacman -Syu sfml`
 
 ###### CentOS, Fedora and other [RPM-based distros](https://en.wikipedia.org/wiki/Category:RPM-based_Linux_distributions)
 
 `sudo yum -Syu sfml`
 
 ###### Debian, Elementary OS, Linux Mint, Ubuntu and its [flavors](https://ubuntu.com/download/flavours) and other [Debian-based distros](https://www.debian.org/derivatives/)
 
 `sudo apt install libsfml-dev`
