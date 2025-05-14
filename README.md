copy i3 config to i3 directory
```bash
sudo cp config ~/.config/i3/
```
 copy polybar config to polybar directory
```bash
sudo cp config.ini ~/.config/polybar/
```

if you want i3blocks insread of polybar copy i3blocks config to i3blocks directory
```bash
sudo cp config.ini ~/.config/i3blocks/
```

copy launch script to polybar directory
```bash
sudo cp launch_polybar.sh ~/.config/polybar/
```

copy volume and brightness scripts to i3 directory
```bash
sudo volume.sh config ~/.config/i3/scripts/
sudo brightness.sh config ~/.config/i3/scripts/
```

copy picom config to picom directory
```bash
sudo cp picom.conf ~/.config/picom/
```

make it executable
```bash
sudo chmod +x launc_polybar.sh
sudo chmod +x brightness.sh
sudo chmod +x volume.sh
```
If you want Blue config rename config.blue to config and i3blocksconfig to config


