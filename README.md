# SSH PY
A ssh host manager for the windows terminal 

## Setup 
First you need to install python to run this program. 

Then download this repository to a folder on your computer.

Open windows terminal and go to settings.

Click open settings.json.

Paste the following json profile into the settings.json at the bottom of your profile lists.

```json
{
    "commandline": "python <location to main.py file use \\ to define a slash>",
    "hidden": false,
    "icon": "https://cdn3.iconfinder.com/data/icons/logos-and-brands-adobe/512/267_Python-512.png",
    "name": "SSH PY",
    "startingDirectory": "Put this to where you installed SSH PY's main.py file ",
    "tabTitle": "SSH PY"
}
```

On the profile you pasted edit `commandline` to `python` and then the location of the main.py file e.g `python C:\SSHPY\main.py` then do the same on the `startingDirectory` but without the `python` and the `main.py` e.g `C:\SSHPY\`

Then save the profile.

Reopen the terminal and you should be able to see the SSH PY tab with a python icon.

Now run the program from the drop down menu. It should take you so a setup that asks you for your hosts.
