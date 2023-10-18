# IMPORTANT INFORMATION
*NOTE: This is repository to used to transfer files to the Esports Room PC that will be used to host the CS2 Server, HUD, and TS3 Server.*

# TS3 Server
1. Unzip the file and send the admin token to *`Admin`*
2. Run the TS3 server.
3. The admin will create two channels: `CS RED` and `VAL RED`
3. Have clients connect to their appropriate channels `https://drive.google.com/file/d/1dJPCfb1yeRSQdGkVD_3IFtG842GI5jGT/view?usp=sharing`.
4. Make sure all clients are able to hear and speak to each other, and PTT binds are properly setup, if needed.

# CS2 Server Installation
1. Use the `CS2-INSTALL.bat` file to install the CS2 server.
2. Use the `CS2-UPDATE.bat` file to update the CS2 server.
3. Use the `CS2-SERVER.bat` file to run the CS2 server (Make sure to edit it for the correct map).

- *Once the server is setup the observer should join the GOTV or the Spectators team and run the* `cs2-overlay.exe`
- *This will link the overlay to OBS and the caster can spectate the game as intended.*

# CS2 OVERlAY
1. Download the CS2 Overlay executable: https://github.com/drweissbrot/cs-hud/releases/latest/download/cs-hud-win.exe and put it into the `/CS-OVERLAY` folder.
2. Put the `gamestate_integration_drweissbrot_hud.cfg` and the `overly.cfg` in the `/cfg` folder of the observers CS2 install.
3. Run the `cs-hud-win.exe` file and make sure that OBS is capturing the overlay in a browser source (`http://127.0.0.1:31982/hud?transparent`).
4. Observer will then execute the `overlay.cfg` file in-game.
