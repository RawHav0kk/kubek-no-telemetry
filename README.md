# kubek-minecraft-dashboard
Kubek - Web Minecraft servers dashboard

# Why this fork?
Kubek is a project licensed under gpl-3, as stated on the repository of the creator. This means, that the project can be forked by anyone and for any reason. Lately I noticed that the project has an ["EULA"](https://kubek.seeroy.ru/eula_en.html) which the end user is forced to accept. This end user agreement feels shady (Legally I am not able to access its legitimacy), as it allows the creator to collect telemetry data and "store, analyze, destroy and transfer the collected statistical data from servers under its control". I reject this and due to the project being licensed under GPL-3, I have a full legal right to fork and redistribute this modified version. This version removes any data collection that I theme predatory. Data collection links have been removed, functions that send web requests to remote hosts in order to send telemetry data have been removed. 

**Features:**
- Linux and Windows supported
- Pure SPA UI
- Plugins and mods manager
- Real-time console
- Server.properties editor
- FTP server included
- Web file manager
- Users and roles system
- Integration with Telegram bot

**Tested and working cores**:
- **NEW** Bedrock Edition servers supported
- All popular PaperMC versions (all PaperMC forks (Tuinity, Airplane, Purpur, etc.) more likely will be work too)
- Spigot 1.8 - 1.18.2 (not included all versions)
- Forge 1.12.2 - 1.19.2 (not included all versions)
- Velocity 1.19.3

**Natively supported cores:**
- Official Vanilla Server
- PaperMC
- Spigot
- Waterfall
- Velocity
- Purpur
- Magma
- Forge (upload installer)

# Extensions system

To create your own extension use [this example repo](https://github.com/Seeroy/kubek-extension-example)

# Installation

Download and launch [latest release](https://github.com/Seeroy/kubek-minecraft-dashboard/releases/latest)

**OR**

Clone repository and install modules
**Node.js >= 16 required!**
```
git clone https://github.com/Seeroy/kubek-minecraft-dashboard.git
cd kubek-minecraft-dashboard
npm install
```

Start after installation
```
node app.js
```)

# Used frameworks/technologies
- Node.js
- Express
- Socket.io
- Flowbite
