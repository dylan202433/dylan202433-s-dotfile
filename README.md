First of all, Install the newest Hyprland using this guide depend on your Distro:

yay -S hyprland-git

Base setups 💻:

    Install waybar, Rofi, Dunst, kitty terminal, swaybg, swaylock-fancy, swayidle, pamixer, light, Brillo:

yay -S waybar-hyprland rofi dunst kitty swaybg swaylock-fancy-git swayidle pamixer light brillo

Required Fonts

https://github.com/ryanoasis/nerd-fonts/releases/download/v2.2.2/JetBrainsMono.zip

https://github.com/ryanoasis/nerd-fonts/releases/download/v2.3.3/Iosevka.zip

yay -S ttf-font-awesome
cp -r ./configs/* ~/.config/
Once you download them and unpack them, place them into ~/.fonts or ~/.local/share/fonts.

Then run this command for your system to detect the newly installed fonts.

fc-cache -fv
Copy Files 💾Copy Files 💾

git clone https://github.com/dylan202433/dylan202433-s-dotfile.git
cd dylan202433-s-dotfile
cp -r ./config/* ~/.config/
