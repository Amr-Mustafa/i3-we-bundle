# i3-we-bundle
A python script for automatically retrieving usage information for your WE's home internet plan.

## Installation for i3blocks

### Clone this repository
```
git clone https://github.com/Amr-Mustafa/i3-we-bundle
cd i3-we-bundle
```

### Place the python script in
```
mkdir -p ~/.config/i3/scripts/
mv we.py ~/.config/i3/scripts/
```

### Add the following to your i3blocks.conf file
```
[internet]
type=custom/script
interval=3600
command=~/.config/i3/scripts/we.py
label=WE
markup=pango
```
