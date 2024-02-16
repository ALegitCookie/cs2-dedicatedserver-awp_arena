# Counter Strike 2 Dedicated Server - Awp Arena Gamemode
This is a drop-in AWP Arena Gamemode setup for Counter Strike 2 Dedicated Servers

# WARNING: ONLY DO THIS ON A SERVER USED SPECIFICALLY FOR AWP ARENA ONLY!
Putting these files on your server will overwrite gamemode configs, which can do unwanted things if you host multiple gamemodes on one server.
If you are using this, I recommend following the instructions and doing this on a fresh server ONLY, and understand that this server will ONLY be used for the AWP Arena gamemode.


#Installation

#Creating a new server (for beginners)
First, We are going to make a fresh install of Counter Strike 2 Dedicated Server. If you know how to do so, go ahead and do it now.

If you are a beginner who does not know how to make a CS2 server, no worries. I'm going to show you a super easy way to create and manage a CS2 server (on windows). If you are on linux, please find an installation tutorial elsewhere.
We're going to be making this server through an application called WindowsGSM, to automate server updates and backups!

1. Install .NET Framework Runtime (https://dotnet.microsoft.com/download/dotnet-framework/net472)
2. Download the WindowsGSM exe (https://windowsgsm.com/products/windowsgsm-desktop/)
3. Create a folder in the location where you would like your gameservers, as well as the WindowsGSM application, to be stored. Name this folder "WindowsGSM".
4. Place the WindowsGSM exe file INSIDE of the WindowsGSM folder you just made.
![1](https://github.com/ALegitCookie/cs2-dedicatedserver-awp_arena-gamemode/assets/39338269/fd7f04e0-3c78-45a5-9fac-d5b64632fac1)

5. Open WindowsGSM so it can create the necessary folders needed to continue.
6. Close WindowsGSM once these folders are auto-created in the WindowsGSM folder.
![3](https://github.com/ALegitCookie/cs2-dedicatedserver-awp_arena-gamemode/assets/39338269/bbde27af-9ad2-4217-925d-00e80048acf0)


7. Download the latest release of the WindowsGSM.CS2 Plugin(https://github.com/ohmcodes/WindowsGSM.CS2/releases/tag/latest)
This will allow us to install the CS2 server on WindowsGSM

8. Extract the zip file and drag the "CS2.cs" folder into the folder WindowsGSM -> Plugins
![2](https://github.com/ALegitCookie/cs2-dedicatedserver-awp_arena-gamemode/assets/39338269/38ac9821-0213-45aa-b973-8009f53fd0ec)

9. Open WindowsGSM and press the puzzle icon in the bottom left. You should see the CS2 Plugin listed. If not, try pressing "Reload Plugins".
10. Now it's time to install the CS2 Server. Go to Servers -> Install Gameserver. Then for the "Game Server" dropdown, select "Counter Strike 2 Dedicated Server". Also, type in a name for you to identify your server.
![4](https://github.com/ALegitCookie/cs2-dedicatedserver-awp_arena-gamemode/assets/39338269/321eb62c-98e5-48bb-9518-5916308e1023)

Go ahead and press the install button. After a minute or so, you should see the installation progress in the Install Log Box. It is now installing the CS2 server. Please be patient, depending on your compouter setup and wifi speed, this could take upwards of 30 minutes.
![5](https://github.com/ALegitCookie/cs2-dedicatedserver-awp_arena-gamemode/assets/39338269/aa918408-75b9-4465-893b-2c15caad6c35)

Note: (If the installation fails, go ahead and close WindowsGSM and go to the Windows GSM folder -> Servers, and delete the folder named "1". This will delete the failed server install and now you can attempt the installation again.)



