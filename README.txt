ABILITY CHAOS: RNG v0.7
Open index.html in a browser (needs internet for three.js, PeerJS and the font).
Online: one player clicks Online > Host room and shares the 4-letter code; friends click Join.
If joining fails when opened from a file, serve the folder (e.g. python3 -m http.server) or upload it to any static host.

Controls: WASD move · SHIFT run · SPACE jump · Q dash · click/F punch (hold) · 1-3 abilities · B block
          R roll (at Rolling Island) · E interact · L lobby · V first/third person · H help
          Mouse look: move the mouse (after the first click) or right-drag. Arrow keys turn too.

v0.3: Autosaves to this browser (localStorage). Settings has Save now / Export / Import so you can back up or move your save.
Title screen runs a live bot-vs-bot fight; bots also fight each other in the main world.
v0.4: Bigger map, click = punch, abilities on 1-3, compact UI, slot-machine roll button (R) above the hotbar.
v0.5: Removed island labels, punch animation, upgraded effects, random death messages, kill feed.
v0.6: Lobby (L) with Home, Gear, Luck, Quests, Index, Odds, Online, Log and Settings, instead of the side panel.
      Gear, luck and potions buy from the lobby from anywhere. First-person camera (V). Random bot names.
      Smarter bots: target by distance and health, kite, strafe, dodge, lead shots, retreat and heal.
v0.7: Bots have three ability slots and use whichever fits the moment (heals, speed boosts, gap closers, ranged attacks).
      Ability effects scale with rarity: heavier casts and impacts, light beams, rising sparks, bigger projectiles.
      Bot casts show the ability name. Cutscene for Mythical and up (rarity 5+): click or press a key to skip.
