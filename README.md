<h1 align=center>BACKUP VredditDownloader</h1>
<p align=center>A bot for reddit that provides downloadable links for v.redd.it videos</p>


## Table of Contents

* [About the Project](#about-the-project)
  * [Usage](#usage) 
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)

## About The Project

Videos hosted on the social media platform www.reddit.com are nearly impossible to download, especially with sound. To make sharing easier, I decided to write my own bot that provides an easy way to download them. 

Since 2018, I run it on my own Raspberry Pi at home.

Currently, the bot account is [VredditDownloader](https://www.reddit.com/user/VredditDownloader). 


### Usage

If you just want a quick download link, mention "u/VredditDownloader" as a comment under any reddit post or link containing a video, or send a private message containing the link. The bot will reply within a few seconds.

You can find more info [at the bot's reddit profile](https://www.reddit.com/user/VredditDownloader/comments/cju1dg/info).


## Getting Started

To host your own video download bot, follow these simple example steps.
    

### Prerequisites

* Python3
* A Reddit Account
  

### Installation


* Clone the repo

      git clone https://github.com/JohannesPertl/vreddit-download-bot.git
    
* Create a reddit app
* Fill in the credentials in a [praw.ini file](https://praw.readthedocs.io/en/latest/getting_started/configuration/prawini.html)
* Fill in the bot configuration in [config.yaml](config.yaml)
* Install the requirements

      pip install -r requirements.txt


## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.


## Contact
The person that actually made this
johannes.pertl@edu.fh-joanneum.at

