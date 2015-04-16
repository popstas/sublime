# Sublime Text 3 config

About config sync - (https://packagecontrol.io/docs/syncing)

## Install

1. Install Package control plugin - (https://packagecontrol.io/installation)

2. Copy config dir
```
config_dir="~/.config/sublime text 3"
if [ -d "$config_dir" ]; then
	cd "$config_dir/Packages"
	mv User User_backup
	git clone https://github.com/popstas/sublime.git User
fi
```

3. Run Sublime Text and wait.
