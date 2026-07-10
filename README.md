# Captain Multi Chat — Setup

Captain Multi Chat puts Twitch, Kick, and YouTube chat in one OBS dock.

## What you need

- Windows 10 or 11 (64-bit)
- [OBS Studio 32 or newer](https://obsproject.com) (64-bit)

## Install (about 2 minutes)

1. **Close OBS** all the way (check the system tray too).
2. Download **[CaptainMultiChat-Setup.exe](https://github.com/Daywon21/captain-multi-chat-releases/releases/latest)**.
3. Run the installer. Allow admin if Windows asks.
4. Open OBS.

## Turn on OBS WebSocket

This is needed for the on-stream chat overlay.

1. In OBS go to **Tools → WebSocket Server Settings**.
2. Check **Enable WebSocket server**.
3. Leave the port at **4455** unless you know you need something else.
4. Click **OK**.

## Open the dock

1. In OBS go to **Docks → Captain Multi Chat**.
2. The chat panel should show up.

If it says it cannot connect to OBS, go back and make sure WebSocket is on.

## Connect your accounts

1. In the dock, open **Settings**.
2. Connect each platform you use:
   - **Twitch**
   - **Kick**
   - **YouTube**
3. Save / finish when each one says connected.

Tip: Stay signed in on those sites in your browser. That makes reconnects easier.

## Set up the stream overlay (optional)

1. In Settings, find **Stream overlay (OBS)**.
2. Pick your chat **Browser Source**.
3. Captain Multi Chat fills in the overlay URL for you.

## Portable install (optional)

If you prefer a zip:

1. Download **[CaptainMultiChat-Portable.zip](https://github.com/Daywon21/captain-multi-chat-releases/releases/latest)**.
2. Unzip it.
3. Double-click **Install Captain Multi Chat**.
4. Follow the same OBS steps above.

## If something goes wrong

| Problem | Try this |
|--------|----------|
| Dock missing | Restart OBS → **Docks → Captain Multi Chat** |
| Cannot connect to OBS | Enable WebSocket (port 4455) |
| Platform not connected | Settings → log out → connect again |

## Where your logins are stored

Your sessions stay on your PC here:

`%APPDATA%\CaptainMultiChat\vault.enc`

Nothing is uploaded to our servers for login storage.

## Help / downloads

- [Latest release](https://github.com/Daywon21/captain-multi-chat-releases/releases/latest)
- [All releases](https://github.com/Daywon21/captain-multi-chat-releases/releases)

© Captain Dark
