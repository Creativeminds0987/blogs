## What is WSL??

# WSL?
WSL {Windows [Subsystem](https://en.wikipedia.org/wiki/System#Subsystem) for [Linux](https://en.wikipedia.org/wiki/Linux)} is an optional feature of windows 10, which helps us to run Linux programs to run natively on [Windows 10](https://en.wikipedia.org/wiki/Windows_10). This makes windows compatible to run [Linux](https://en.wikipedia.org/wiki/Linux) programs and [bash shell](https://en.wikipedia.org/wiki/Bash_(Unix_shell)).

## Requirements to install WSL:
Windows10(64-bit)

## Designed by?
[Microsoft](https://en.wikipedia.org/wiki/Microsoft) in partnership with [Canonical](https://en.wikipedia.org/wiki/Canonical_(company)).

## Uses of WSL?
- WSL helps windows users to access powerful core programs like GNU tools (such as `awk, find, grep, sed`)}. But, not all Linux programs can be used in WSL but some [command line](https://en.wikipedia.org/wiki/Command-line_interface) Linux applications.
- WSL comes with software package tools {like `apt & dpkg`}. ###How to install WSL?
- Open a [PowerShell](https://en.wikipedia.org/wiki/PowerShell) window(as administrator). Don't know how to open click here-> [see video](https://www.youtube.com/watch?v=crcfYnazTB8&feature=emb_title)
- Type `Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux` and press enter.
- Then, You will be prompted to reboot your computer.
- Type `Y` and press enter and your computer starts to restart.
- After the computer reboots, open a new command prompt window and run bash (by entering `bash` and clicking enter).
- After running the above command.
- `Bash` will inform you `no distribution is installed`
- It will give you a [URL](https://aka.ms/wslstore) for downloading one distribution from the Windows Store.
- Now, copy the link and paste it into a web browser and click enter.
![in store](https://res.cloudinary.com/practicaldev/image/fetch/s--Ngw2_gvF--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/n2rwmsekyycs94y8lacu.jpg)
- Click the distribution of your choice, then click Get to install the distribution you want.
- When the installation completes, click Launch and you will see a message
`Installing, this may take a few minutes...`