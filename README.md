![Rocknet Logo](https://github.com/user-attachments/assets/04d7a167-a35b-474f-b86b-4d81ec6b3ac4)

<h1 align="center"> Rocknet </h1>

<p align="center"> A Server-side Implementation for Roblox 2016 Source Code  </p>
<p align="center"><b>NOTE:</b> Roblox Recently Did some changes to their APIs, some assets may return <b>401 Unauthorized</b>, so use <b>local</b> branch.</p>

<h2 align="center"> Setting the Server Up </h2>

**IMPORTANT:** Its in Alpha Stage, so do not want much from it, its just a basic server for make the game work.

1. Install **[XAMPP](https://www.apachefriends.org/index.html)** and **[HxD](https://mh-nexus.de/en/downloads.php?product=HxD20)** to host the server locally
2. Download the repository
3. Open **XAMPP** and Start just the **Apache**
4. Press **Explorer** and head over to **htdocs** folder
5. Extract the **Rocknet** folders to that place
6. Enter the hosts file by doing: `"C:\Windows\System32\Drivers\etc\hosts"`
7. Add these lines:
```
127.0.0.1 roblox.com 
127.0.0.1 www.roblox.com 
127.0.0.1 api.roblox.com
127.0.0.1 versioncompatibility.api.roblox.com
127.0.0.1 clientsettings.api.roblox.com
127.0.0.1 assetgame.roblox.com
```
8. Save the file and close it
9. Have fun!
