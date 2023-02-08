<!-- PROJECT SHIELDS -->
[![][readme-shield]][readme-url]
[![][version-shield]][version-url]
![][contributors-shield]
[![][issues-shield]][issues-url]
![][lisence-shield]
![][keywords-shield]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="#">
    <img src="https://imgur.com/DFOtb1J.jpg" alt="Logo" width="400" style="border-radius: 50%;">
  </a>

  <!-- <h3 align="center">[COD]Squad Bot</h3> -->

  <p align="center">
    <a href="https://github.com/ALCHElVlY/cod-squad-bot/issues">Report Bug</a>
    ·
    <a href="https://github.com/ALCHElVlY/cod-squad-bot/issues">Request Feature</a>
    ·
    <!-- <a href="https://discord.com/api/oauth2/authorize?client_id=1049822652166049822&permissions=1099796909104&scope=bot%20applications.commands">Invite to Discord!</a> -->
    <a href="https://discord.com/api/oauth2/authorize?client_id=1049822652166049822&permissions=1099796909104&scope=bot%20applications.commands" target="_blank">Invite to Discord!</a>
  </p>
</p>



<!-- ABOUT THE PROJECT -->
<div>
  <h2>About The Project</h2>
  <p>
    A Discord bot to create and manage Call of Duty squad channels. Whether solo, or in quads, Squad Bot can help you manage private squad channels in your Discord server! 
    If squad fill is not for you, and you would rather team up with those you know from Discord, whether in a private server shared with just friends, or an entire Call of Duty community server, Squad Bot can help you quickly form the right squad!
    Key features include:
    <ul>
      <li>Quick and easy squad channel creation</li>
      <li>Priority speaker for squad leader</li>
      <li>AutoScrub for cleaning up empty squad channels (keeps your Discord nice and tidy)</li>
      <li>Customizable AutoMod rule for monitoring squad channel objectives (prevents profanity, etc.)</li>
    </ul>
  </p>
</div>


<!-- BUILT WITH -->
<div>
  <h2>Built With</h2>
  <p>
    The following technologies were used in Squad Bot's development.
    <ul>
      <li><a href="https://www.mongodb.com/home" target="_blank">MongoDB</a></li>
      <li><a href="https://expressjs.com/" target="_blank">ExpressJS</a></li>
      <li><a href="https://nodejs.org/en/" target="_blank">NodeJS</a></li>
      <li><a href="https://discord.js.org/#/" target="_blank">DiscordJS</a></li>
    </ul>
  </p>
</div>



<!-- DOCUMENTATION -->
<div>
  <h2>Documentation</h2>
  <p>
    When you invite Squad Bot to your Discord, it automatically creates an automod rule for your server.
    This rule is used by the bot to monitor squad objectives when users attempt to create new squads.
    You cannot remove this rule, but you can add words or keyphrases to the rule in order to increase the security measure.
  </p>
  <br>
  <img src="https://i.imgur.com/QvxxKfd.png" alt="Automod Rule" width="650">
  <br>
  
  <br>
  <p>
    By default commands are disabled for everyone, and with Discord's latest update (at the time of writing these docs), server owners
    now have more power and control over who gets to use a bot's commands. As a Discord Server owner, you will need to setup some
    overrides for any command you wish to be usable by those in your server. The best way to handle this is to create or assign a valid
    role with override persmissions to a particular slash command as shown in the example below.
  </p>
  <img src="https://i.imgur.com/1xJLlWV.png" alt="Slash Command Permissions Example" width="650">

  <br>
  <p><code>*Squad Bot performs better when given a role with administrator permissions.</code></p>

  <h3><u>Setting Up Squad Categories</u></h3>
  <p>
    Squad Bot requires a category channel to be created for each game mode you wish to use it for.
    This category will be used to order squad channels according to Call of Duty game modes.
    To create a category for Squad Bot, use the settings command to update <code>squad categories</code>
  </p>
  <img src="https://i.imgur.com/Q6snV8u.gif" alt="Squad Bot Tutorial - Adding Squad Categories" width="650">
  
  <br>
  <p><code>*Only the squad categories setting is used in the bots current configuration.</code></p>
</div>



<!-- ROADMAP -->
<div>
  <h2>Roadmap</h2>
  <p>
    See the <a href="https://github.com/ALCHElVlY/cod-squad-bot/issues" target="_blank">open issues</a> for a list of known issues,
    and <a href="https://github.com/users/ALCHElVlY/projects/5" target="_blank">project board</a> for a list of planned updates, and their status.
  </p>
</div>


<!-- MARKDOWN LINKS & IMAGES -->
[readme-shield]: https://img.shields.io/badge/readme%20style-standard-blue.svg?style=for-the-badge
[readme-url]: https://github.com/ALCHElVlY/cod-squad-bot#readme
[version-shield]: https://img.shields.io/github/v/tag/ALCHElVlY/cod-squad-bot?label=version&style=for-the-badge
[version-url]: https://github.com/ALCHElVlY/cod-squad-bot/releases
[issues-shield]: https://img.shields.io/github/issues/ALCHElVlY/cod-squad-bot?color=blue&style=for-the-badge
[issues-url]: https://github.com/ALCHElVlY/cod-squad-bot/issues
[contributors-shield]: https://img.shields.io/github/contributors/ALCHElVlY/cod-squad-bot?color=blue&style=for-the-badge
[lisence-shield]: https://img.shields.io/github/package-json/license/ALCHElVlY/cod-squad-bot?style=for-the-badge
[keywords-shield]: https://img.shields.io/github/package-json/keywords/ALCHElVlY/cod-squad-bot?color=blue&style=for-the-badge
