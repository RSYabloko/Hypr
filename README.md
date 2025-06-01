#Установка yay:

    git clone https://aur.archlinux.org/yay.git

#Установка или из AUR, который скомпилирует последнюю версию исходного кода: Hyprland:

    yay -S hyprland-git

#Установка из репы, который скомпилирует последнюю версию исходного кода: Hyprland:

    pacman -S hyprland

#Установленные пакеты:

  	sudo pacman -Sy waybar fish wofi sddm pavucontrol alacritty fastfetch thunar hyprpaper hyprlock 

#Вспомогательные пакеты:

    yay git pavucontrol wine pulseaudio pulseaudio-alsa alsa-utils

#Установленные шрифты:

    sudo pacman -S ttf-jetbrains-mono-nerd ttf-ionicons noto-fonts-emoji

#Драйвера Nvidia

    sudo pacman -S nvidia-dkms nvidia-settings nvidia-utils

#Остальные пакеты

    sudo pacman -S telegram-desktop discord steam firefox obsidian

#Amnezia
    
    yay -S amneziawg-dkms amneziawg-tools

#Vencord

    sh -c "$(curl -sS https://raw.githubusercontent.com/Vendicated/VencordInstaller/main/install.sh)"

#GPG & Pass

    sudo pacman -S gnupg pass

#Фильтр синего

    sudo pacman -S wlsunset

    Запуск:

    wlsunset -t 4499 -T 4500
