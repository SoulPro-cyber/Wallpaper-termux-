# Wallpaper-termux-
pkg update
pkg upgrade
pkg install git wget curl termux-tools
git clone https://github.com/username/wallpaper-repo.git
cd wallpaper-repo
wget -O wallpaper.jpg https://example.com/wallpaper.jpg
termux-wallpaper wallpaper.jpg
