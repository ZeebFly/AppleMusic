
### 💻 Apple Music Deployment Guide on Local Server or VPS  🗄️
<br>
<details>
<summary><strong>Ubuntu 20.04 / 22.04 Setup</strong></summary>

#### 🧩 Step-by-Step Installation

**1. Update & Upgrade the System**
```bash
sudo apt-get update && sudo apt-get upgrade -y
```

**2. Install Required Packages**
```bash
sudo apt-get install python3-pip ffmpeg -y
```

**3. Upgrade pip**
```bash
sudo pip3 install -U pip
```

**4. Clone the Repository**
```bash
git clone https://github.com/TheTeamAlexa/AlexaMusic && cd AlexaMusic
```

**5. Install Python Requirements**
```bash
pip3 install -U -r requirements.txt
```

**6. Create `.env` File**
```bash
cp sample.env .env
```
> Now edit `.env` with your configuration variables.

**7. Edit Environment Variables**
```bash
vi .env
```
> - Press `I` to start editing.  
> - Press `Ctrl + C`, then type `:wq` to save and exit.  
> - Use `:qa` to quit without saving.

**8. Install and Start Tmux**
```bash
sudo apt install tmux && tmux
```

**9. Start the Bot**
```bash
bash start
```
</details>

<br>
<details>
<summary><strong>Ubuntu 24.04 Setup</strong></summary>

#### 🧩 Step-by-Step Installation

**1. Update & Upgrade the System**
```bash
sudo apt-get update && sudo apt-get upgrade -y
```

**2. Install Required Packages**
```bash
sudo apt-get install python3-pip ffmpeg -y
```

**3. Upgrade pip**
```bash
sudo pip3 install -U pip
```

**4. Clone the Repository**
```bash
git clone https://github.com/TheTeamAlexa/AlexaMusic && cd AlexaMusic
```

**5. Install Python Requirements (Ubuntu 24 specific)**
```bash
pip install -r requirements.txt --break-system-packages
```

**6. Create `.env` File**
```bash
cp sample.env .env
```
> Edit `.env` with your bot configuration.

**7. Edit Environment Variables**
```bash
vi .env
```
> - Press `I` to edit.  
> - Press `Ctrl + C`, then type `:wq` to save.  
> - Use `:qa` to quit without saving.

**8. Install and Start Tmux**
```bash
sudo apt install tmux && tmux
```

**9. Start the Bot**
```bash
bash start
```
</details>

<br>
<summary><b>sᴄᴀʟɪɴɢᴏ</b></summary>

<br>

ɴᴏᴡ ʏᴏᴜ ᴄᴀɴ ᴅᴇᴘʟᴏʏ ᴀʟᴇxᴀ ᴍᴜsɪᴄ ᴏɴ sᴄᴀʟɪɴɢᴏ ɪɴᴛʀᴏᴅᴜᴄᴇᴅ ʙʏ @ITZ-ZAID

<br>

<p><a href="https://my.scalingo.com/deploy?template=https://github.com/TheTeamAlexa/AlexaMusic"> <img src="https://cdn.scalingo.com/deploy/button.svg" width="220" height="38.45"/></a></p>


<summary><b>ᴅᴇᴘʟᴏʏ ᴛᴏ ʜᴇʀᴏᴋᴜ</b></summary>
<br>

> ʜᴇʀᴏᴋᴜ ʜᴀs ᴛᴡᴏ ᴠᴀʀs [ʜᴇʀᴏᴋᴜ_ᴀᴘɪ_ᴋᴇʏ & ʜᴇʀᴏᴋᴜ_ᴀᴘᴘ_ɴᴀᴍᴇ] ғᴏʀ ᴜᴘᴅᴀᴛᴇʀ ᴛᴏ ᴡᴏʀᴋ.
> ʙʏ sᴇᴛᴛɪɴɢ ᴛʜᴏsᴇ ᴛᴡᴏ ᴠᴀʀs ʏᴏᴜ ᴄᴀɴ ɢᴇᴛ ʟᴏɢs ᴏғ ʏᴏᴜʀ ʜᴇʀᴏᴋᴜ ᴀᴘᴘ, sᴇᴛ ᴠᴀʀ, ᴇᴅɪᴛ ᴠᴀʀ, ᴅᴇʟᴇᴛᴇ ᴠᴀʀs , ᴄʜᴇᴄᴋ ᴅʏɴᴏ ᴜsᴀɢᴇ ᴀɴᴅ ᴜᴘᴅᴀᴛᴇ ʙᴏᴛ.
> ᴛʜᴏsᴇ ᴛᴡᴏ ᴠᴀʀs ᴀʀᴇ ɴᴏᴛ ᴍᴀɴᴅᴀᴛᴏʀʏ, ʏᴏᴜ ᴄᴀɴ ʟᴇᴀᴠᴇ ᴛʜᴇᴍ ʙʟᴀɴᴋ ᴛᴏᴏ.
<br>
<h4> ᴄʟɪᴄᴋ ᴛʜᴇ ʙᴜᴛᴛᴏɴ ʙᴇʟᴏᴡ ᴛᴏ ᴅᴇᴘʟᴏʏ ᴀʟᴇxᴀ ᴏɴ ʜᴇʀᴏᴋᴜ</h4>    
<p><a href="http://dashboard.heroku.com/new?template=https://github.com/TheTeamAlexa/AlexaMusic"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-red?style=for-the-badge&logo=heroku" width="200"/></a></p>

<br>

<summary><b>⚡ ʀᴇɴᴅᴇʀ</b></summary>

<br>

<p><a href="https://render.com/deploy?repo=github.com/TheTeamAlexa/AlexaMusic"> <img src="https://img.shields.io/badge/Deploy%20to-Render-blue?style=for-the-badge&logo=render" width="220" height="33"/></a></p>

<br>
