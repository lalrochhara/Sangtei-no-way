![Sangtei](https://i.ibb.co/3W5Wq9v/image-1.png)

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/a56e54398402417cb19a7d08c62b492b)](https://app.codacy.com/gh/lalrochhara/Sangtei/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://perso.crans.org/besson/LICENSE.html) [![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com) [![Updates channel!](https://img.shields.io/badge/Join%20Channel-!-red)](https://t.me/SangteiUpdates)

# Sangtei 
Sangtei is the female deuteragonist of the anime/manga series Fairy Tail. She is an S-class Mage from the Guild Fairy Tail. Like most Fairy Tail members, she shows great loyalty and dedication to Makarov and the guild.

</br>

We created this bot by inspired from [SaitamRobot](https://github.com/AnimeKaizoku). Which was originally forked of Marie bot which was developed by [PaulSonOfLArs](https://t.me/PaulSonofLars). You can't say we directly copied everything from [SaitamRobot](https://github.com/AnimeKaizoku). This repo have too many bugs we fixed and re write whole code and add other hundreds modules too make bot enjoyable for you. We hope you show us our support. Give this repo <b>5 Star & Fork & Deploy</b>. If you have any query regarding this bot contact us on our support group we are available thier to help you
<br>
</br>

<b> You can use original bot which was deployed by me already on telegram </b>  [Sangtei On Telegram](https://t.me/Sangtei_Groupbot)

### Heroku Deploy
<b>Deploying</b>
<p align="center"><a href="https://heroku.com/deploy?template=https://github.com/lalrochhara/Sangtei"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-black?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

### Mandatory Vars 📒
```
[+] Make Sure You Add All These Mandatory Vars. 
    [-] APP_ID:   You can get this value from https://my.telegram.org
    [-] APP_HASH :   You can get this value from https://my.telegram.org
    [-] OWNER_USERNAME : Your Telegram username. Without @.
    [-] REDIS_URI :First go to redislabs.com and create your database and get your endpoint and default password.
Now save your redis url in this format </br> redis://:your-redis-default-password@your-redis-endpoint. .
    [-] TOKEN: Get from botfarther
    [-] DATABASE_URL: from elephantsql.com if deploy in vps or in heroku ignore this.
    [-] OWNER_ID: ur id
    [-] JOIN_LOGGER: Channel Id E.g. -1004672929 
    [-] EVENT_LOGS: Channel Id E.g. -1004672929 
    [-] SUPPORT_CHAT': 'Your Public channel name like @Sangtei_Justice'
[+] The Sangtei won't run without setting the mandatory vars.
```

### Self-hosting (For Devs) ⚔
```sh
# Install Git First (apt-instll git)
$ git clone https://github.com/lalrochhara/Sangtei
$ cd Sangtei
# Install All Requirements 
$ pip3 install -r requirements.txt
# Rename ./Sangtei/sample_config.py to config.py
$ cd Sangtei 
$ mv sample_config.py config.py
$ nano config.py
# Then Fill All vars
# Start tmux session to keep active session even if you close your vps session.
$ sudo apt-install tmux
$ tmux 
# Start Bot 
$ python3 -m Sangtei
# Exit Tmux Session
# Press Ctrl+B and then D.
```


## Credits
▪️ [AnimeKaizoku](https://github.com/AnimeKaizoku) - <b> For base code </b> </br>
▪️ [PaulSonOfLArs](https://t.me/PaulSonofLars) - <b> For Main Work </b> </br>
▪️ [Me - Sohail Khan](https://t.me/sohailkhan_anime) - <b> This repo </b> </br>
