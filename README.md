# AutoFarmCatizen

![Catizen logo](https://catizen.ai/static/images/index-logo-mobile.png)

# ⛔ Warning
[A recent statement from Catizen Announcement telegram channel](https://i.imgur.com/QlxZWfQ.jpeg) declares that users can get removed from the airdrop whitelist for using scripts or "other cheats". From now on, you are using the script completely at your own risk, as safety of your Catizen account's airdrop validity is not guaranteed.

# ⚠️ Attention
This script is only supported in the **Desktop** version of **Telegram**. It is **not intended for the web version**, so you may encounter bugs and/or errors.

## Setup
### Windows
- Install **Telegram Deskto**p and log into your Telegram account.
- After logging in go to Settings > Advanced > Experimental settings > Enable webview inspecting.
- Reopen your **Telegram Desktop**.
- Open [webview mode](https://telegra.ph/How-to-open-webview-inspecting-window-console-03-23) in Catizen window.
- press `Ctrl + Shift + i` to open console.

### Mac
- Install **Telegram Desktop** and log into your Telegram account.
- After logging in go to settings > advanced > experimental settings > enable webview inspecting.
- Reopen your **Telegram Desktop**.
- Open [webview mode](https://telegra.ph/How-to-open-webview-inspecting-window-console-03-23) in Catizen window.
- Open Safari > Develop > Your macbook device > Telegram > game.catizen.ai, it will open Telegram's webview inspector.

## Installation (Execution)
Access the **Telegram** webview inspection console ([guide on how to do it](https://telegra.ph/How-to-open-webview-inspecting-window-console-03-23))

Paste the following command into the command prompt:

```javascript
var unixTime=Date.now(); var url='https://raw.githubusercontent.com/RBJunior1/Auto-Catizen-Tool/main/AutoCatizen.js'+'?'+unixTime; fetch(url).then(response=>response.text()).then(script=>eval(script));

```
 * Now you only need to fetch the link (execute the script) and the magic will begin.
 * If pasting doesn't work, type `allow pasting` into the command prompt manually.

# What this script does:
* Enables the "Auto" button, which includes
   - Auto cats merging
   - Automatically using free boost on cooldown
   - Auto purchasing cats when you have enough money

## Known issues:
```None```
