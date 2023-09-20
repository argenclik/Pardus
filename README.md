# Pardus
## Pardus Komutları

etap+pardus!

sudo apt update && sudo apt full-upgrade -yq

sudo sh -c "$(wget -O- http://indir.pardus.org.tr/PARDUS/pardus19to21.sh)"

rm ~/.local/share/keyrings/*

lsattr 

chattr -i test.txt

sudo su root

sudo apt-get -f install
sudo dpkg --configure -a
sudo apt update
sudo apt install printer-driver-escpr
sudo apt install printer-driver-all
