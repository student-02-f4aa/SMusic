

### 🖥️ VPS Deployment Guide

  - Update and Install Dependencies: `sudo apt update && sudo apt upgrade -y && sudo apt install -y ffmpeg git python3-pip python3-venv tmux nano`

  - Create the Virtual Environment: `python3 -m venv .venv`

  - Activate Virtual Env: `source .venv/bin/activate`

  - Clone the Repository: `git clone https://github.com/TheTeamVivek/YukkiMusic && cd YukkiMusic`

  - Install Python Requirements: `pip install -r requirements.txt`

  - Copy and Edit Environment Variables:

    Copy the sample environment file: `cp sample.env .env`

    Edit the variables in the .env file: `nano .env`

  After editing, press `Ctrl+X`, then `Y`, and press **Enter** to save the changes.


  -  Run the Bot: `bash start`

  - Keep the Bot Running with tmux: `tmux`

To exit the **tmux session** without stopping the bot, press `Ctrl+b`, then `d`.


