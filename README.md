# vc
Venus Capture

# Ever felt a need to do screencapture of a specific window from the command-line?

> The challenge is that although screencapture works awesome if you know the windowid, knowing it is no easy task.

> And, you also have to worry about saving the screencapture from your pastebuffer before you accidentally take a new one. :(

# See if you like `vc`

> Finds the window id of the application from all desktops & screens. ['Zoom Meeting' in my program for testing.]

> Automatically saves a screencapture to the ~/Documents folder.

> At the end of the setup, we will have a short command `vc` that you can use to capture the window you want.


# Install (We will use python3 with a virtualenv)

> 1. Installing virtualenv using `pip3 install virtualenv`

> 2. Create a virtualenv using - `` python3 -m virtualenv venv --python=`which python3` `` 

> 3. Start using the newly created virtualenv `venv` using - `. venv/bin/activate`

> 4. Install the Quartz python library using - `pip install pyobjc-framework-Quartz` 
  
    [Ref: https://pypi.org/project/pyobjc-framework-Quartz/]

> 5. Say, on your MacOS, run the following command to save it to your `~/.zshrc`

`git clone https://github.com/vyanamandra/vc; cd vc; chmod +x vc install-as-alias; ./install-as-alias`
    

# Taking screencaptures is now easy. 

> Just type `vc` and your captures are saved under `~/Documents`

    Note: Remember to source your ~/.zshrc using `. ~/.zshrc` or just log out of the terminal and log back in.


  
