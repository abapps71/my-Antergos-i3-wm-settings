# configs: 
by that mean: my configs i use on i3-wm

[![i3-wm-joekamprad](http://kamprad.net/wp-content/uploads/2017/09/i3wm-24-9-2017.png)](https://youtu.be/QA7eLgKS8js)
{click on the screenshot opens screencast}

What i use for i3-wm:

i3-wm: https://i3wm.org/ + i3-gnome-git: https://github.com/mephux/i3-gnome

my wallpapers: http://kamprad.net/backgrounds/

rofi: https://github.com/DaveDavenport/rofi

i3lock: https://github.com/i3/i3lock

i3blocks: https://github.com/vivien/i3blocks

awesome font: http://fontawesome.io

pamac: https://github.com/manjaro/pamac

vivaldi: https://vivaldi.com/download/

geary: https://github.com/GNOME/geary

xfce4-terminal: https://github.com/xfce-mirror/xfce4-terminal

terminator: https://code.launchpad.net/~gnome-terminator/terminator/gtk3

zsh: http://www.zsh.org/  (ZSH_THEME="gnzh") + https://github.com/zsh-users/zsh-syntax-highlighting

pavucontrol: https://freedesktop.org/software/pulseaudio/pavucontrol/ 

redshift-gtk: http://jonls.dk/redshift/

**As i am on Antergos (Based on Archlinux) i provide package list and AUR list and the commands to create and install:**

**Creating packages lists:**

`pacman -Qqen > packages-repository.txt`

`pacman -Qqem > packages-AUR.txt`

**restore this:**

`pacman --needed -S - < packages-repository.txt`

`cat packages-AUR.txt | xargs yaourt -S --needed --noconfirm`

---
All scripts and configs are done by remixing other configs, to use them you need to change directories inside.
And Just as they are, without any guarantee!!!
