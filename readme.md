#### My config for the [Suckless simple terminal st](https://st.suckless.org).

Source code :

    git clone https://git.suckless.org/st

The config is edited in the *config.def.h*.  
The installation will create a copy named *config.h*:

    rm -f config.h
    sudo make uninstall
    sudo make clean install

[Patches](https://st.suckless.org/patches/):  
Download them in the folder */patches*, patch and reinstall:

    patch --merge -i /path/to/patch.diff


---
requirements:
    fontconfig
    libx11-dev
    libxft-dev

---
To see the modifier list:

    xmodmap

To see key's names:

    xev


---
#### Credits
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.
