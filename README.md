 DEEP VAULT — Game Manual

 🎮 Play Here
https://sargam172.github.io/Deep-Vault-game/



 How to Start

1. Open the link on your phone or computer
2. Choose your settings:
    ☑️ HeadTilt Steering — Move by tilting phone
    ☑️ Sound — Turn music on/off
3. Tap "DIVE IN"



 Controls:
 
 Move diver  Tilt phone OR drag finger on screen 
 Collect coins  Touch them 
 Avoid sharks  Swim away 

 Game Rules:

 Goal  Collect 30 gold coins 

 Level 1  Collect 15 coins → Unlocks Level 2 
 Level 2  Collect 15 more coins → WIN! 
 Shark bite  Lose 15 points 



 OnScreen Info

 Top left — Coins collected
 Top right — Time & Score
 Right side — Scoreboard



 Troubleshooting

 Issue  Fix 

 Tilt not working  iPhone: Settings → Safari → Motion & Orientation → ALLOW 
 No sound  Tap 🔊 button, check phone volume 
 Black screen  Turn OFF "Stereoscopic VR Mode" 



Created by Sargam Arora 

Some Prompts used were:
Prompt 1 — Initial debugging
"My A-Frame game works on laptop but not on mobile. After 'DIVE IN', the game screen is blank/black on phone. Please fix so the game canvas is visible on mobile. Keep all features."

Response used: Added CSS position:fixed and z-index to force canvas visibility on mobile.

Prompt 2 — Head-tilt movement fix
"In this game diver is only moving in a sleeping line not up or down based on my head movement. How to Fix that."

Response used: Recalibrated tiltBeta mapping from beta - 45 with higher Y sensitivity (5.0 vs 4.0) to enable vertical movement.

Prompt 3 — Full screen on mobile
"Just make it seen on full screen."

Response used: Added position:fixed, width:100% !important, height:100% !important to canvas and viewport-fit=cover meta tag.

