# Mac Setup
Setup for new Macs or Linux machines in case of an EMP attack. Installs: systems, installations, dotfiles, Sublime Text 3. Run shell via a click.


## Instructions

### Linux
```shell
cd
curl -LOk https://github.com/kengz/mac_setup/archive/master.zip
unzip master.zip
cd mac_setup
bash setup_linux
```

### MacOS
```shell
cd
curl -LOk https://github.com/kengz/mac_setup/archive/master.zip
unzip master.zip
cd mac_setup
bash setup
```

Or if you like GUI, download the executable `setup` and **RIGHT-CLICK** on it to run. 

The mac `setup` will download the [Sublime Settings](https://github.com/kengz/sublime_settings) repo to `~/Documents/` for you to setup Sublime too.

If you want `LaTeX` and `Octave`, then run the `setup_extra` too. The `LaTeX` here is `basicTex`, which is just 100Mb.