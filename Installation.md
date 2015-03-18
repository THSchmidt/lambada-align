# Installation #

## Linux ##

### Download ###
Download the LAMBADA archive from the [project download](http://code.google.com/p/lambada-align/downloads/list) website.

### Unpack ###
Extract the files of the compressed `tar.gz` archive:
```
tar -xvzf lambada.tar.gz
```
LAMBADA should work already now by typing `perl lambada/lambada`.

### Optional Installation Steps ###
Copy the folder into your `lib` directory:
```
cp -r lambada/ ~/lib/
```

Make LAMBADA executable:
```
chmod 755 ~/lib/lambada/lambada
```

Set a soft link to the LAMBADA executable in your `bin` directory:
```
ln -s ~/lib/lambada/lambada ~/bin/lambada
```