<div align="center">
  
  <h1>Minecraft Java+Bedrock Server</h1>

  <h3>MC Server Version 1.17.1</h3>

  <h4>Template Created by <a href="https://discord.io/LIMYAW/">Mashwishi</a> | Powered by <a href="https://geysermc.org/">Geysermc</a> & <a href="https://github.com/PaperMC">PaperMC</a></h4>

 
<!-- [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/B0B14A4MU) -->
<!-- <a href="https://discordbotlist.com/bots/814580247973986314"><img src="https://discordbotlist.com/api/v1/bots/814580247973986314/widget"></a> -->
<!-- [![support][support-image]][support-invite]-->

 <p align="center">
            <a href="https://ko-fi.com/mashwishi"> <img align="center" src="https://ko-fi.com/img/githubbutton_sm.svg" /></a>
          <br/><br/>
         </p>



  
 [![Contributors][contributors-shield]][contributors-url]
 [![Forks][forks-shield]][forks-url]
 [![Stargazers][stars-shield]][stars-url]
 [![Issues][issues-shield]][issues-url]
 [![MIT License][license-shield]][license-url]
 <br>

</div>

---

<strong>A Pre-made Minecraft Server 1.17.1 that supports Java Edition and Bedrock Edition to play in one running server. Java(PC/Laptop) players can join Bedrock users playing at PC/Laptop, Mobile Device, PlayStation 4 and Nintendo Switch.

<img src="https://i.imgur.com/LHTxVDB.jpg" width="100%"/>

---

### Pre-made Set up Features:
- :file_folder: All needed files is included
- :cop: Account Security Included
- :+1: Latest Version of Minecraft
- ⚙ Pre-Configure Settings
- :smiley: Easy to setup


<h2 align="center">Setup Tutorial</h2>

<div align="center">
<p>Recommended Hosting (<i>This is affiliated link, Not officially endorsed or sponsored by Pebblehost</i>)</p>
  <a href="https://billing.pebblehost.com/aff.php?aff=1764"><img alt="PebbleHosting - Discord Bot Hosting" src="https://pebblehost.com/src/img/branding/banner1.gif"></a>
</div>

> If you have questions related to Geyser and FloodGate, please contact [Geyser](https://discord.gg/geysermc), This project is created for set-up tutorial only. **You'll be on your own when you try to add plugins and update to higher version.**


## Getting Started
This is how you will set-up and host your cross-version and cross-platform Minecaft Server on Windows or Hosting Services.


### Requirements

- Java Version 16 (Important)
- Atleast 5GB of Ram (Minimum for 1.17.x)
- Quad-Core CPU/Processor or higher (4 Cores)

### Installation
1. Clone the repo
   ```sh
   git clone https://github.com/mashwishi/Minecraft-Server-Java-and-Bedrock-Support.git
   ```
2. Configure run.bat and modify `5G` to your desire ram.
   ```bat
    :: IGNORE THIS IF YOU'RE NOT SELF-HOSTING, KINDLY DON'T INCLUDE THIS FILE!
    java -Xmx5G -Xms5G -jar paper.jar nogui
    PAUSE
   ```
3. After that kindly run `start.bat` file. This will start your minecraft server
4. If the server prints `Done!` to the console kindly type `Stop` and hit enter
5. Once your server is closed, Navigate to `plugins` folder and open `floddgate`
6. Copy the `key.pem` file and go back to `plugins` folder open `geyser` folder
7. Paste the `key.pem` file to `geyser` folder
8. To edit the MOTD of your Bedrock Server open `config.yml` at `geyser` folder
   ```yml
    #Rename the motd1, motd2 and server-name strings
    motd1: "A Minecraft server"
    motd2: "Supports Java & Bedrock Server"
    server-name: "myserver"
   ```
9. Once every thing is done you can now start your service again to your panel or `start.bat` for self-hosting

### Highly Recommended:
[Please read this page on how to setup Geyser for any supported platform](https://github.com/GeyserMC/Geyser/wiki/Setup) and [Geyser frequently asked questions](https://github.com/GeyserMC/Geyser/wiki/FAQ).


### Reminders:

- If you are using hosting services and not self-hosting do not include the `server.properties` and `start.bat` since `server.properties` will be generated by your host and `start.bat` is not the way to start your minecraft server on hosting services look for `start` button to your panel to start your server in a hosting service.

## Issue/Suggestions

If met any issues, go [here](https://github.com/Mashwishi/Minecraft-Server-Java-and-Bedrock-Support/issues) to report bug and create new issue for supporting

## Github Repository

Template Made by Mashwishi, project [Here](https://github.com/Mashwishi/Minecraft-Server-Java-and-Bedrock-Support)

---

<div align="center">
<p>Recommended Hosting (<i>This is affiliated link, Not officially endorsed or sponsored by Pebblehost</i>)</p>
  <a href="https://billing.pebblehost.com/aff.php?aff=1764"><img alt="PebbleHosting - Discord Bot Hosting" src="https://pebblehost.com/src/img/branding/banner1.gif"></a>
</div>

[support-invite]: https://discord.gg/WAh8eaF2Qq
[support-image]: https://discordapp.com/api/guilds/779997243159216149/widget.png?style=banner2

[donate-link]: https://www.paypal.me/NCMC
[donate-image]: https://i.imgur.com/R2SxfKG.png

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/mashwishi/Minecraft-Server-Java-and-Bedrock-Support.svg?style=for-the-badge
[contributors-url]: https://github.com/mashwishi/Minecraft-Server-Java-and-Bedrock-Support/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/mashwishi/Minecraft-Server-Java-and-Bedrock-Support.svg?style=for-the-badge
[forks-url]: https://github.com/mashwishi/Minecraft-Server-Java-and-Bedrock-Support/network/members
[stars-shield]: https://img.shields.io/github/stars/mashwishi/Minecraft-Server-Java-and-Bedrock-Support.svg?style=for-the-badge
[stars-url]: https://github.com/mashwishi/Minecraft-Server-Java-and-Bedrock-Support/stargazers
[issues-shield]: https://img.shields.io/github/issues/mashwishi/Minecraft-Server-Java-and-Bedrock-Support.svg?style=for-the-badge
[issues-url]: https://github.com/mashwishi/Minecraft-Server-Java-and-Bedrock-Support/issues
[license-shield]: https://img.shields.io/github/license/mashwishi/Minecraft-Server-Java-and-Bedrock-Support.svg?style=for-the-badge
[license-url]: https://github.com/mashwishi/Minecraft-Server-Java-and-Bedrock-Support/blob/master/LICENSE
