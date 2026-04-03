
## Overview

This section will go through how to set up [**mGBA**](https://mgba.io/),
an emulator for the [**Game Boy Advance (GBA)**](https://en.wikipedia.org/wiki/Game_Boy_Advance) console.
It is free, open-source, and easy to install, making it a popular choice for many desktop gamers.

## Installing mGBA

The first step is to install the emulator, if you do not already have it.

1. **Visit** the official downloads page at [mgba.io](https://mgba.io/downloads.html).
2. **Download** a version suitable for your operating system.
    For Windows users, you will see the following options:

    - Windows (portable .7z archive)
    - Windows (installer .exe)
    - Windows (64-bit, portable .7z archive) < Recommended
    - Windows (64-bit, installer .exe)

    !!! Info "32-bit vs 64-bit Windows?"

        The number of bits refer to the sizing of how data is stored on your system.  

        Most modern computers are *64-bit*, so you will probably need one of the latter two options.  
        If you have a 32-bit system, choose between the first two.  

        If you are unsure, you can usually find this information in your system settings.

    ### Using the portable version

    The *.7z archives* are the *portable* versions. These hold everything compressed as a 7-Zip (similar to a *.zip* file).
    This is the recommended way to install mGBA, as you only need to **extract** the files to get started.
    This allows you to choose where to store it on your computer, and also lets you keep your game files with mGBA.  

    Many newer versions of Windows can extract 7-zip without additional setup,
    but some systems may need a separate extractor from the [**7-zip site**](https://7-zip.link/download.html).  

    !!! Warning

        It is important to store mGBA in a *"common folder"*
        (does not require administrator privileges to access).

        We recommend storing it in a new folder in *Documents* or on your *Desktop*
    
    1. **Click** on the `Windows (64-bit, portable .7z archive)` option to download it.
    2. **Extract** the files.    
        1. **Right-click** on the archive (`mGBA-xx.xx.xx-winxx.7z`).
        2. **Click** either:

            > Extract all

            or

            > Extract with 7-zip

        3. **Choose** a valid location to put the files.

    ![Extracting mGBA portable](../assets/getting-started/extract-1-2.gif){ width=90%  }

    !!! Success

        The contents of the extracted folder should look like this.

        ![mGBA portable folder](../assets/getting-started/mGBA-portable.png){ width=90% }


    ### Using the installer

    The *"installer .exe"* may be useful for people less comfortable with using their file systems.
    
    
    1. **Download** and run the *install wizard* to install mGBA to your computer as an application.



3. **Run** mGBA.exe.
    If the portable version was used, this will be in the extracted folder.  

    If the installer was used, this can usually be accessed from one of the following:

       - A *"Desktop"* shortcut.  
       - the Windows *"Start Menu"*.  

        > Windows-Key :fontawesome-brands-windows: > Search "mGBA"

       - The install location, the default being:

        > C:\Program Files\mGBA

!!! Success

    The app should look something like this once opened.

    ![mGBA main screen](../assets/getting-started/homescreen.png){ width=80% 

## Storing ROMs

ROM stands for *Read-Only Memory*, which refers to data that cannot be modified - often stored in
cartridge or disc form. In the context of games and emulation, it also refers to copies or "dumps" of the game
that was originally on these cartridges.  

mGBA is compatible with the following types of ROMs:  

- Game Boy (*.gb* files).  
- Game Boy Color (*.gbc* files).  
- Game Boy Advance (*.gba*).  

The next step is to find a ROM(s) and figure out where to keep them on our computer.  

1. **Download** a ROM.  

    Getting ROMs can be done in a couple ways:  

      - **Acquire** them online.
      - **Upload** them from a physical copy of the game.

    !!! Danger

        Downloading ROMs online can be risky and can be illegal depending on where you live!  
        
        Here is a list of things to check if you decide to acquire them this way:  

        - **Avoid** any ROMs that come as *.exe* files, these are likely malicious programs.  
        - **Cross-check** ROM sites with communities such as [r/Roms on Reddit](https://www.reddit.com/r/Roms/wiki/index/).  
        - **Stay away** from any buttons or links that do not match the look of the rest of the site.  

    !!! Info

        Learn more about uploading (also known as "ripping") game ROMS
        [here](https://wiki.provenance-emu.com/using-provenance/roms/ripping-roms#cartridge-dumping).

2. **Move** the ROM files to a folder of your choosing.

    In your file explorer, drag the *.gb*, *.gba*, or *.gbc* file
    to a *"common folder"* (does not require administrator privileges to access).
    If the ROM is in a *.zip* folder, there is no need to extract it.  

    If using the portable version, we recommend creating a *"Games"* folder in the same location as *"mGBA.exe"*.

    !!! Note

        By default, mGBA will also store your game save progress as *".sav"* files in the same folder as the ROM.  

        To change this behaviour, **edit** the *"Path Settings"* in mGBA:

        > Tools > Settings > Interface > Path

## Loading ROMs

The next step is to use load these ROMs to play the games stroed in them.
There are a couple ways to do this.

### Loading individual ROMs


## Conclusion
