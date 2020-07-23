![Avatar](img/ava.png)
![Slogan](https://i.imgur.com/vfEgGLU.png)
=====================

[![Python3](https://img.shields.io/badge/python-3.7-blue.svg)](https://github.com/Der-Eddy/discord_bot)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/Der-Eddy/discord_bot/master/LICENSE)
[![Discord Server](https://img.shields.io/badge/Support-Discord%20Server-blue.svg)](https://discord.gg/kPMbPDc)

**ATTENTION: This bot uses the new version of [discord.py v1.0+](https://github.com/Rapptz/discord.py/tree/rewrite), if you want to use my bot with the old legacy discord.py version check out the [legacy branch](https://github.com/Der-Eddy/discord_bot/tree/0.18.10-legacy).**
This is mostly a german discord chat bot made with [discord.py v1.0+](https://github.com/Rapptz/discord.py).  
If you are looking for a python discord bot to host for yourself, you should rather take a look at [Red Bot](https://github.com/Twentysix26/Red-DiscordBot) if you want a highly customizable self-hosted python bot. Shinobu is only meant to be run on my own server.

Using `pip install discord.py` will install the latest discord.py version.

Commands List
-------------
**Info:** Diese Liste gilt für den Standardprefix `:`

### Generic ###

Command und Aliases | Beschreibung | Nutzung
----------------|--------------|-------
`:help` | Zeigt eine Liste aller öffentlichen Commands | `:help`, `:help kawaii`

### Forum ###

Command und Aliases | Beschreibung | Nutzung
----------------|--------------|-------
`:epvpis`, `:epvp` | Sucht nach einem Benutzernamen auf Elitepvpers | `:epvpis Der-Eddy`
`:epvpverify`, `:verify` | Verifiziert einen Discord Benutzer über Elitepvpers | `:epvpverify`, `:epvpverify Der-Eddy`

### Utility ###

Command und Aliases | Beschreibung | Nutzung
----------------|--------------|-------
`:status`, `:s`, `:uptime`, `:up` | Listet einige Informationen zum Bot aus | `:status`
`:ping` | Misst die Response Time | `:ping`
`:github` | Verlinkt zu diesem GitHub Repo | `:github`
`:about`, `:info` | Informationen über Shinobu Oshino | `:about`
`:log`, `:archive` | Archiviert den Log des derzeitigen Channels und läd diesen als Attachment hoch | `:log 10`
`:invite` | Erstellt einen Invite Link für den derzeitigen Channel | `:invite`
`:whois` | Gibt Informationen über einen Benutzer aus | `:whois @Der-Eddy#6508`
`:emoji`, `:e` | Gibt eine vergrößerte Version eines angegebenen Emojis zurück | `:emoji Emilie`
`:emojis`| Gibt alle Emojis aus auf welche der Bot Zugriff hat | `:emojis`
`:server`, `:serverinfo`, `:guild`, `:membercount` | Gibt Informationen über die derzeitge Discord Guild aus | `:server`
`:timer`, `:reminder` | Setzt einen Timer und benachrichtigt einen dann | `:timer 13m Pizza`, `:timer 2h`
`:source`| Zeigt den Quellcode für einen Befehl auf GitHub an | `:source kawaii`
`:commands`| Zeigt an wie oft welcher Command benutzt wurde seit dem letzten Startup | `:commands`
`:roleUsers`| Listet alle Benutzer einer Rolle auf | `:roleUsers Admins`
`:games` | Zeigt welche Spiele wie oft auf dem Server gerade gespielt werden | `:games`
`:spoiler` | Erstellt ein GIF Bild welches beim Hover einen Spoiler Text anzeigt | `:spoiler`
`:ranks`, `:rank`, `:role`, `:roles` | Auflistung aller Ränge oder beitritt eines bestimmten Ranges | `:ranks`, `:ranks Python'`
`:addvote` | Fügt Emotes als Reactions hinzu für Abstimmungen/Umfragen | `:addvotes`, `:vote`, `:votes`

### Anime ###

Command und Aliases | Beschreibung | Nutzung
----------------|--------------|-------
`:kawaii` | Gibt ein zufälliges kawaii Bild aus | `:kawaii`
`:nsfw` | Vergibt die Rolle um auf die NSFW Channel zugreifen zu können. **Nur auf Eddys Server!** | `:nsfw`
`:hello`, `:wave`, `:hi`, `:ohaiyo` | Nonsense gifs zum Hallo sagen | `:hello`
`:nep`, `:nepu`, `:topnep` | Can't stop the Nep | `:nep`
`:pat` | /r/headpats Pat Pat Pat :3 | `:pat @Der-Eddy#6508`
`:ratewaifu`, `:rate`, `:waifu` | Bewertet deine Waifu | `:ratewaifu Shinobu`
`:anime`, `:anilist` | Sucht auf AniList.co nach einem Anime und gibt die Basis-Informationen zurück | `:anime Mushishi`
`:manga` | Sucht auf AniList.co nach einem Manga und gibt die Basis-Informationen zurück | `:manga Air Gear`
`:saucenao`, `:sauce`, `:iqdb` | Versucht die Quelle eines Anime Bildes zu finden | `:saucenao https://i.imgur.com/nmnVtgs.jpg`

### Fun ###

Command und Aliases | Beschreibung | Nutzung
----------------|--------------|-------
`:java`, `:javascript`, `:nodejs`, `:js` | Weil Java != Javscript | `:java`
`:csharp`, `:c++`, `:c#`, `:objective-c` | Wie soll man da überhaupt durchblicken??? | `:csharp`
`:praise` | Praise the sun | `:praise`
`:css` | Counter Strike: Source | `:css`
`:countdown` | It's the final countdown | `:countdown`
`:neko`, `:cat`, `:randomcat` | Zufällige Katzen Bilder nyan~ | `:neko`
`:random`, `:rand` | Gibt eine zufällige Zahl oder Member aus | `:random`, `:random coin`, `:random 6`, `:random 10 20`, `:random user`
`:steinigt` | Monty Python | `:steinigt @Ravenstorm#1191`
`:hype`, `:hypu`, `:train` | HYPE TRAIN CHOO CHOO | `:hype`
`:xkcd` | Zeigt den letzten oder zufälligen XKCD Comic | `:xkcd`, `:xkcd random`
`:reaction`, `:r`, `:addreaction` | Fügt der letzten Nachricht ein Emoji als Reaction hinzu oder einer bestimmten Nachricht | `:reaction ok_hand`, `:reaction sunglasses 247386709505867776`
`:pun`, `:witz`, `:joke` | Weil jeder schlechte Witze mag | `:pun`
`:tags`, `:tag` | Erstellt tags oder gibt diese aus | `:tags new hentai https://youtu.be/tg3rG-e6haw`, `:tags del 2`, `:tags hentai`

### Mod ###

Command und Aliases | Beschreibung | Nutzung
----------------|--------------|-------
`+clear`, `:prune` | Löscht mehere Nachrichten auf einmal. **MOD ONLY** | `:purge 100`
`:kick` | Kickt ein Mitglied mit einer Begründung. **MOD ONLY** | `:kick @Der-Eddy#6508`, `:kick @Der-Eddy#6508 Spammt Werbung`
`:ban` | Bannt ein Mitglied mit einer Begründung. **MOD ONLY** | `:ban @Der-Eddy#6508`, `:ban @Der-Eddy#6508 Spammt Werbung`
`:unban` | Entbannt ein Mitglied mit einer Begründung. **MOD ONLY** | `:unban 102815825781596160`
`:bans` | Listet aktuell gebannte User auf. **MOD ONLY** | `:bans`
`:removereactions` | Entfernt alle Emoji Reactions von einer Nachricht. **MOD ONLY** | `:removereactions 247386709505867776`
`:permissions` | Listet alle Rechte des Bots auf. **ADMIN OR BOT OWNER ONLY** | `:permissions`
`:hierarchy` | Listet die Rollen-Hierarchie des derzeitigen Servers auf. **ADMIN OR BOT OWNER ONLY** | `:hierarchy`
`:setrank`, `:setrole`, `:sr` | Vergibt einen Rang an einem Benutzer. **MOD ONLY** | `:setrole @Der-Eddy#6508 Member`
`:rmrank`, `:rmrole`, `:removerole`, `:removerank` | Entfernt einen Rang von einem Benutzer. **MOD ONLY** | `:rmrole @Der-Eddy#6508 Member`






Support
-------------
Utilities+ Support Server: `https://discord.gg/N5cvQT7`

