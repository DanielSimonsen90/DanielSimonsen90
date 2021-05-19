# DanielSimonsen90
### C# • JavaScript • TypeScript • HTML 

***

## Info
**How did you come up with your name?**
My name is Daniel Simonsen, and my iconic number is 90 so put those together and there we go.

**What caught your interest into coding?**
Ever since I was introduced to Minecraft's redstone mechanics, I loved to make my own contraptions, and as time passed by, moved on to simple Excel calculations and little RPG game designing using [RPG Maker XP](https://www.rpgmakerweb.com/products/rpg-maker-xp).
Finally, I got the opportunity to be taught very basic HTML and your classic traffic light assignment using C - this is where I knew I wanted to keep programming and therefore started my "Datatechnician with Speciality in Programming" education.

**What is your favorite project?**
My favorite project is my Discord Bot, Pingu.
Pingu is my first JavaScript project, which I incoporated a little TypeScript with.
My plan for Pingu, is for him to become the best Discord bot with famous features from other bots like:
* [MEE6](https://mee6.xyz/dashboard) & [Dyno](https://dyno.gg/account)'s moderation system
* [Rythm](https://rythm.fm/) & [Groovy](https://groovy.bot/)'s music commands and ability to play sounds from other providers than YouTube; i.e. Spotify & SoundCloud
* [ReactionRoles](https://top.gg/bot/550613223733329920)'s reaction roles
* [Poll Bot](https://top.gg/bot/pollbot)'s polls
* [GiveawayBot](https://giveawaybot.party/)'s giveaways
* [Miki](https://top.gg/bot/miki)'s daily streaks, chat achievements & ability to marry a member

**Favorite language?**
JavaScript.
Even though I'm taught in C# in school, ever since I got into JavaScript and TypeScript, I felt like there was finally a language that did what I wanted in an easy way.
I also really enjoy coding in C#, but in terms of async code, handling events, being able to only give the programmer very specific parameter options using TypeScript's "type" keyword, the simplicity of making an array/object and let alone the spread syntax (...), are all situations I much rather would use JavaScript than C#.
Besides, most people dislike JavaScript for the fact it isn't 100% type dependent, which I can understand, but it doesn't bother me personally, as all I want is being able to see what type of object I'm dealing with - and I can still do that either by using TypeScript or by defining a summary for the function I'm in.

***

## Links
[<img alt="Pingu Invite" src="https://media.discordapp.net/attachments/791312246063104033/844436535813734400/The_Blogger.png" width="32px" height="32px" />](https://discord.com/api/oauth2/authorize?client_id=562176550674366464&permissions=8&scope=applications.commands%20bot)
[<img alt="Pingu Support Server" src="https://media.discordapp.net/attachments/805500972305612851/835532058679574549/Badge_Support_Team.png" width="32px" height="32px" />](https://discord.gg/gbxRV4Ekvh)
[<img alt="Portfolio Website" src="https://media.discordapp.net/attachments/791312246063104033/844437480555544576/New_Logo.png" width="32px" height="32px" />](https://danhosaurportfolio.azurewebsites.net/)

***

## Contact?
**If you wish to contact me, you can do so by using my:**
* [Discord](https://discord.com/channels/@me/245572699894710272)
* [Email](mailto:danielsimonsen90)

***

<p align="center">
  <img id="danielSimonsen90Activity" align="center"/>
</p>

<script>
const linkOptions: {
    default: {
        "show_icons": "true",
        "count_private": "true",
        "hide_border": "true",
        "icon_color": "fff"
        "bg_color": "05B281"
        "title_color": "fff"
        "text_color": "fff"
    },
    custom: {
        "icon_color": "999999"
        "bg_color": "404040"
        "title_color": "FF5132"
        "text_color": "B7B7B7"
    }
}

let useDefault = false;
let link = "https://github-readme-stats.vercel.app/api?username=danielsimonsen90&"
let linkParams = useDefault ? 
    linkOptions.default : 
    Object.keys(linkOptions).reduce((result, current) => {
        const { custom } = linkOptions
        result[current] = custom[current] !== null ? custom[current] : linkOptions.default[current];
    }, {});

link += Object.keys(linkParams)
    .map(prop => `${prop}=${linkParams[prop]}`)
    .join('&');

let img = document.getElementById('danielSimonsen90Activity');
if (!img) return;

img.src = link;
</script>