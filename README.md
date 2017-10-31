# zshrc
zsh設定管理用リポジトリ


#設定とか
/boot/grub/themes/poly-light-master/theme.txt
/etc/default/grub
:ブートローダーの設定ファイル

sudo grub-mkconfig -o /boot/grub/grub.cfg

/boot/grub/fonts/
sudo grub-mkfont --verbose --range=0x0-0x7f --size=18 --output=./uzura-18.pf2 /usr/local/share/fonts/u/uzura.ttf

sudo nano /etc/fonts/conf.d/65-nonlatin.conf
fc-cache -f -v


うずらフォント
