## OH Leaderboard Bot

This is a simple discord bot for periodically posting new scores from the Open Hexagon community leaderboards (not official leaderboards). Written in Python with [discord.py](https://discordpy.readthedocs.io/en/latest/index.html).

## Quickstart
1. Install python (preferably 3.13 or newer) if it isn't installed already. Navigate your terminal to the source directory.

2. Install the dependencies, `discord` and `requests`. Using a virtual environment is recommended for distro-agnosticy. 
    - `python -m venv bot-env`
    - `source bot-env/bin/activate`
    - `pip install discord requests`
    - **(Optional, but recommended)** Use a static type checker to avoid annoying typing-related errors when modifying code. You can use [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance), or the FOSS [basedpyright](https://docs.basedpyright.com/latest/) extension.
3. Create a file called `token.txt`, containing solely the authentification token for your bot, which you can find in the [Discord Developer Portal](https://discord.com/developers/applications).

4. Run the bot with `python main.py`

