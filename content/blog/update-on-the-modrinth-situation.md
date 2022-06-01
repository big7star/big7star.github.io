---
title: "Update on the Modrinth Situation"
draft: false
publishdate: 2022-06-01T12:55:09-05:00
summary: "Information about MechanicCraft's availabilty on Modrinth, and why this happening at all."
image: "modrinth-curseforge-changes.png"
imagealttext: "An artiscal rendition of a judge and the accused, with their heads being the Curseforge logo as the judge and the Modrinth logo as the accused"
---
Hey everyone - 

Got another update for y'all. (It's a long one so TL;DR is at the bottom)

MechanicCraft will unfortunately remain unavailable for download on Modrinth for at least the next few days, and here's why:

For those who don't know, when MechanicCraft was first released almost two years ago it was available only on Curseforge. Life was good then - there was no big mean wolf trying to stomp out third party minecraft launchers forcing them to use their own less than desirable alternative. But, times change. And so in an effort to promote the atmosphere of cooperation and goodwill that I believe is a central part of the Minecraft modding community, I decided to make MechanicCraft available for download on Modrinth, in addition to Curseforge. 

This is where we starting hitting a snag - the vast majority of the mods that MechanicCraft contains are only available on Curseforge. Downloading a modpack from Curseforge is simple - you can just download each required mod from the service itself. Modrinth doesn't have that luxury, and since the platform is relatively new and because not a lot of mod authors have chosen to make their mods available on Modrinth, it's a bit tricky to make modpacks that are entirely independent from Curseforge. 

To solve this problem, Modrinth would, during modpack install, download the mods from Curseforge using their content distribution network or CDN. This method bypassed Curseforge's official API allowing Modrinth unrestricted access to files hosted on Curseforge. To be clear, I don't support this method of doing modpacks on Modrinth because it deprives mod authors of downloads that would count towards their reward program income on Curseforge and I was not aware that this was how it was done until recently - but that's a topic for another day.

Recently, as detailed in this recent [blog post by Modrinth](https://blog.modrinth.com/modpack-changes/) Curseforge took notice and demanded that Modrinth remove all content hosted on the platform that makes use of the Curseforge CDN by the end of the month. This is why MechanicCraft has been removed from Modrinth - it is one of the many projects on Modrinth reliant on the Curseforge CDN. (To be clear, I removed MechanicCraft myself, not the Modrinth team).

So what now?

The short answer is I don't know. There are a lot of factors that will influence if MechanicCraft will be able to return to Modrinth, the largest being whether or not the mods that MechanicCraft uses have will permit me to host the modpack on Modrinth at all. In order for me to be able to do this, I need to ensure that each and every mod in MechanicCraft meets these conditions (quoted directly from the blog post):

> 1. The mod is licensed under terms that allow for redistribution. The pack author is responsible for following the terms of the license.
> 2. General or individual permission is granted from the mod author. This can be in the form of a message from the author or a statement made on a mod's project description granting permission to use it in modpacks.

Essentially what I will need to do is go though each mod and verify that the mod:
1. has a license that permits their mod to be re-distributed on Modrinth,
2. has a message posted on their project page allowing their mod to be re-distributed for modpack use, or
3. already exists on Modrinth, which bypasses the need to do 1 and 2

The good news is that I have already begun this process, and you can track how far I am using [this Trello card](https://trello.com/c/1gPukQ1r). The bad news is that this is a lot of work and it will take me a significant amount of time to complete it and re-release the modpack once I am done with this process. I also do not know if a re-release will even be possible; if too many of MechanicCraft's mods prevent re-distribution, or if a key mod that MechanicCraft relies on for its core gameplay does not allow re-distribution, then MechanicCraft will have to remain a Curseforge-only modpack for the foreseeable future.

**TL;DR:** MechanicCraft is remaining unavailable for download on Modrinth for now, and I will need to complete a lot of work to ensure that I can re-release it (and depending on certain conditions, a re-release may not be possible at all).

I will keep you all as up-to-date on the situation as I can. Thank you for your patience, and for playing my modpack <3.

-beansquared