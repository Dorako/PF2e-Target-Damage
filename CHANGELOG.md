# 2.1.0
- Added a "Classic" formatting client setting, putting the names on top of the buttons.
- Removed buttons from the chat message if the token is not owned by the player, i.e. cannot apply damage to it anyway.
- Clicking the names now will either:
  - Select the token if owned by the player.
  - Target the token if not owned by the player.
  - Pan to the token if double clicked.

# 2.0.2
- Fixed bug the Shield button not turning off once used.
- Removed part of the module that referred to outdated `data` property.
- "aaaaaaaaaaaaaa" is now properly translated.
- Fixed "Needs some more CSS touch ups" from 2.0.0. Thank you Dorako for the contribution!

# 2.0.1
- Fixed release workflow not including template files.

# 2.0.0
- Rewritten the module.
- Needs some more CSS touch ups.
- Makes use of the latest PF2e system (v4.6.5).

# 1.5.5 a.k.a. "Can I leave this module alone for 5 minutes?!"
- Fixed damage application not being up to date to v4.6.4 of the Pathfinder 2e system. ([#20](https://github.com/MrVauxs/PF2e-Target-Damage/issues/20))

# 1.5.4
- Fixed damage application not being up to date to v4.6.3 of the Pathfinder 2e system. ([#18](https://github.com/MrVauxs/PF2e-Target-Damage/issues/18))
- Fixed Persistent Damage Conditions being applied to both the target and a selected token. ([#17](https://github.com/MrVauxs/PF2e-Target-Damage/issues/17))


# 1.5.3
- Fixed typo.

# 1.5.2
- Added support for macros modifying the target flags, allowing the manipulating of what targets the module renders.

# 1.5.1
- Fixed an issue with Persistent Damage condition application.

# 1.5.0
- Updated compatibility with Pathfinder 2e system to 4.6.0, making it the new minimum version.
- Integrated the "Apply Persistent Damage Condition" button from PF2e Persistent Damage with the module. Now you don't have to select a token to apply those conditions as well.
- Fixed "Hide Collapsible Buttons" setting not actually hiding the buttons.

# 1.4.1
- Added localization.

# 1.4.0
- Added a button to collapse the damage buttons.
  - With that, improved "Hide original PF2e damage buttons" by allowing you to still access the buttons after they have been hidden. Now they are just automatically collapsed instead.

# 1.3.5
- Fixed release workflow.

# 1.3.4
- Made the module no longer make Foundry complain about using `data` paths.
- Fixed a bug when chat messages would error when a token that has been targeted no longer existed. ([#11](https://github.com/MrVauxs/PF2e-Target-Damage/issues/11))

# 1.3.3
- Fixed #9 Targets is Undefined error on flag-less damage messages.

# 1.3.2
- Fixed the module not working on PF2e 4.4.0
- Enabled previously commented out triple damage buttons.

# 1.3.1
- Fixed the module not working on PF2e 4.3.0

# 1.3.0
- Fixed an issue where damage buttons were shown to all players even if they didn't own the token, thus couldn't apply damage. Now the module hides damage buttons if you don't own the token itself, rather than having the token belong to *any* player.
- Fixed only the first target being highlighted on hover. ([#5](https://github.com/MrVauxs/PF2e-Target-Damage/issues/5))
- Made the module override ignore targeting if the message comes from [PF2e Persistent Damage](https://github.com/CarlosFdez/pf2e-persistent-damage). ([#4](https://github.com/MrVauxs/PF2e-Target-Damage/issues/4))
  - Added a setting to replace the damage buttons with PF2e Target Damage buttons only for persistent damage.
- Fixed some holdover localization issues from Target Lock.

# 1.2.0
- Add token mystification based on "Tokens determine NPC name visibility" system setting.
- Added on hover and double click token selection on target names.
- Removed debug console logs.

# 1.1.1
- Fix styling on hidden target names.

# 1.1.0
- Fix localization breaking everything.
- Add setting to hide original system buttons. ([#1](https://github.com/MrVauxs/PF2e-Target-Damage/issues/1))

# 1.0.1
- Added back classes to buttons
- Added Module Management+ conflicts with Target Lock.
- Fixed localization issue with Shield Block.

# 1.0.0
Release!
