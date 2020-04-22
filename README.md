# Installation

Make sure you have pipenv installed, eitherwise, manually install:
- discord.py
- lavalink

`pip install -U discord.py`

`pip install lavalink`

with pipenv, you can just clone this repository, and run `pipenv install` and it should install all dependencies in the Pipfile.

Make sure you have Lavalink downloaded, go to https://github.com/Frederikam/Lavalink/releases and download the latest version. You will also need at least Java 11, so make sure to download that.

DOWNLOAD JAVA 11 - https://jdk.java.net/java-se-ri/11

DOWNLOAD LAVALINK - https://github.com/Frederikam/Lavalink/releases

You need to make sure that your Java path is configured correctly. Look up a video on how to do that.

Once everything is installed, set up the application.yml file, I already have a sample one you can use in the repository. It will connect to localhost on port 7000 with password "testing". You can change this, but you will also need to modify it in the music.py file to connect to the correct server.

