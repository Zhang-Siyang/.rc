nano:
    set tabtospace
    set tabsize 4
shadowsocks-libev:
    sudo add-apt-repository ppa:max-c-lv/shadowsocks-libev
    sudo cp /etc/shadowsocks-libev/conf.json /etc/shadowsocks-libev/{domain}.json
apt remove:
    sudo apt remove firefox*
    sudo apt remove libreoff*
    sudo apt remove unity-webapps-*
apt install:
    sudo apt install tmux
    sudo apt install zsh
    sudo apt install git
    sudo apt install apt-transport-https
    sudo apt install python-pip
    sudo apt install fctix-googlepinyin
    sudo apt install curl
    sudo apt install android-tools-adb
    sudo apt install jq
    //source ustc
Applications:
    wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
        && sudo nano /etc/apt/sources.list.d/google-chrome.list
Oh My Zsh:
    sh -c "$(wget https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
    nano siyang.^%#%*^&.zsh-theme
other:
    mkdir Wallpapers
    axel -n 16 cachefly.com/100mb.bin
git:
    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"
Keyboard Shortkey:
    /usr/bin/google-chrome-stable
Grub:
    theme Atomic https://github.com/lfelipe1501/Atomic-GRUB2-Theme
SSH:
    ssh-keygen
    ssh-copy-id
pip install:
    genpac
    requests
    bs4
