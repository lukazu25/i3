copy i3 config to i3 directory
```bash
sudo cp config ~/.config/i3/
```
 copy polybar config to polybar directory
```bash
sudo cp config.ini ~/.config/polybar/
```
copy launch script config to polybar directory
```bash
sudo cp launch_polybar.sh ~/.config/polybar/
```

copy volume and brightness scripts to i3 directory
```bash
sudo volume.sh config ~/.config/i3/scripts/
sudo brightness.sh config ~/.config/i3/scripts/
```

make it executable
```bash
sudo chmod +x launc_polybar.sh
sudo chmod +x brightness.sh
sudo chmod +x volume.sh
```
