#### This is my config for the [Suckless simple terminal st](https://st.suckless.org).

Source code :

    git clone https://git.suckless.org/st

The config is edited in the *config.def.h*, the install will create a copy in *config.h*:

    sudo rm -f config.h && sudo make clean install

[Patches](https://st.suckless.org/patches/):  
Download them in the folder */patches*, patch and reinstall:

    patch --merge -i /path/to/patch.diff

---
To see the modifier list:

    xmodmap

To see key's names:

    xev


---
#### Credits
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.
