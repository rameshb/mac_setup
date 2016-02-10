# Mac Setup
Setup for new machines, MacOS or Ubuntu, in case of an EMP attack. Installs: systems, installations, dotfiles, Sublime Text 3.


## Instructions

### Ubuntu
```shell
cd && sudo apt-get install zip unzip && curl -LOk https://github.com/kengz/mac_setup/archive/master.zip && unzip master.zip && mv mac_setup-master mac_setup && bash mac_setup/setup
```

### MacOS
```shell
cd && curl -LOk https://github.com/kengz/mac_setup/archive/master.zip && unzip master.zip && mv mac_setup-master mac_setup && bash mac_setup/setup
```

Or if you don't like the terminal, download the zip and **RIGHT-CLICK** on `setup` to run. 

The `setup_macOS` will download the [Sublime Settings](https://github.com/kengz/sublime_settings) repo to `~/Documents/` for you to setup Sublime too.

If you want `LaTeX` and `Octave`, then run the `setup_extra` too. The `LaTeX` here is `basicTex`, which is just 100Mb.

