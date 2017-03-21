# app_installation
install app's via PPA

sudo apt-get install p7zip p7zip-full vibrancy-colors vivacious-folder-colors-addon vivacious-colors awoken-icon-theme darktable  skype oracle-java8-installer gtk2-engines-murrine:i386 gtk2-engines-pixbuf:i386 libdvd-pkg libavcodec-extra nemo nemo-fileroller k3b handbrake-gtk handbrake-cli anoise telegram uget deluge alarm-clock-applet mypaint mypaint-data-extras inkscape doublecmd-gtk winusb font-manager blender gimp gimp-plugin-registry gimp-gmic deadbeef sublime-text-installer

http://www.opera.com/computer

sudo add-apt-repository ppa:webupd8team/sublime-text-3
sudo apt-get update
sudo apt-get install sublime-text-installer

sudo add-apt-repository ppa:starws-box/deadbeef-player
sudo apt-get update
 sudo apt-get install deadbeef

sudo add-apt-repository ppa:otto-kesselgulasch/gimp-edge
sudo apt-get update
sudo apt-get install gimp
sudo apt-get install gimp-plugin-registry gimp-gmic

sudo add-apt-repository ppa:thomas-schiex/blender
sudo apt-get update
sudo apt-get install blender

sudo add-apt-repository ppa:font-manager/staging
sudo apt-get update
sudo apt-get install font-manager

sudo add-apt-repository ppa:nilarimogard/webupd8
sudo apt-get update
sudo apt-get install winusb

sudo add-apt-repository ppa:alexx2000/doublecmd
sudo apt update
sudo apt install doublecmd-gtk или
sudo apt-get install doublecmd-qt

sudo add-apt-repository ppa:inkscape.dev/trunk
sudo apt-get update
sudo apt-get install inkscape

sudo add-apt-repository ppa:dimula73/krita
sudo apt-get update
sudo apt-get install krita3-testing 

sudo add-apt-repository ppa:achadwick/mypaint-testing
sudo apt-get update
sudo apt-get install mypaint mypaint-data-extras

sudo apt-get install typecatcher
https://apps.ubuntu.com/cat/applications/mahjongepic2/

sudo apt-get install alarm-clock-applet

sudo add-apt-repository ppa:deluge-team/ppa
sudo apt update && sudo apt install deluge

sudo add-apt-repository ppa:plushuang-tw/uget-stable
sudo apt-get update
sudo apt-get install uget

sudo add-apt-repository ppa:atareao/telegram
sudo apt-get update
sudo apt-get install telegram

sudo add-apt-repository ppa:costales/anoise
sudo apt-get update
sudo apt-get install anoise
http://anoise.tuxfamily.org/

sudo add-apt-repository ppa:foobnix-team/foobnix-player  
sudo apt-get update  
sudo apt-get install foobnix

sudo add-apt-repository ppa:stebbins/handbrake-releases
sudo apt-get update
sudo apt-get install handbrake-gtk
sudo apt-get install handbrake-cli

sudo apt-get update
sudo apt-get install k3b

sudo add-apt-repository ppa: noobslab / apps
sudo apt-get update
    sudo apt-get install marlin 

sudo add-apt-repository ppa:webupd8team/nemo
sudo apt-get update
sudo apt-get install nemo nemo-fileroller
killall nemo или nemo -q
nemo

sudo apt-add-repository -y ppa:teejee2008/ppa
sudo apt-get update
sudo apt-get install aptik

sudo add-apt-repository ppa:atareao/atareao
sudo apt update
sudo apt install my-weather-indicator

sudo apt install libavcodec-extra

sudo apt install libdvd-pkg

sudo apt install skype
sudo apt install gtk2-engines-murrine:i386 gtk2-engines-pixbuf:i386

sudo add-apt-repository ppa:webupd8team/java
sudo apt update
sudo apt install oracle-java8-installer

sudo add-apt-repository ppa:pmjdebruijn/darktable-release
sudo apt-get update
sudo apt-get install darktable

sudo add-apt-repository ppa:noobslab/icons
sudo apt-get update
sudo apt-get install awoken-icon-theme

sudo add-apt-repository ppa:ravefinity-project/ppa
sudo apt-get update
sudo apt-get install vivacious-colors 
sudo apt-get install vivacious-folder-colors-addon

sudo add-apt-repository ppa:ravefinity-project/ppa
sudo apt-get update
sudo apt-get install vibrancy-colors 

sudo add-apt-repository ppa:frol/zip-i18n
 sudo apt-get update &&  sudo apt-get upgrade
 sudo apt-get install p7zip p7zip-full 


sudo apt-add-repository ppa:teejee2008/ppa
sudo apt-get update
sudo apt-get install aptik ukuu

скорость
-----------------
sudo sed -i 's/NoDisplay=true/NoDisplay=false/g' /etc/xdg/autostart/*.desktop
cat /proc/sys/vm/swappiness
sudo sysctl vm.swappiness=10
sudo nano /etc/sysctl.d/99-sysctl.conf
vm.swappiness=10
