# Changelog  
  
| modName    | Stack Inline Lights (SIL)                                         |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-NC-SA-3.0                                                   |
| author     | Alexustas and zer0Kerbal                                          |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/202945-*/) |
| github     | (https://github.com/zer0Kerbal/StackInlineLights)                 |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/StackInlineLights)    |
| spacedock  | (https://spacedock.info/mod/2396)                                 |
| ckan       | StackInlineLights                                                 |

## Version 0.9.0.0-release - `<Thank you Alexustas>` edition

* Released
  * 26 Feb 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Sumamary 0.9.0.0

* Update, Lint and modernize all parts
* NEW: lights can blink!
* Create Agency (will be moving out into it's own addon)
* English Localization (complete)
* Updated
  * textures to bc3 DXT5
  * part tags to use stock strings
* Can now search for `SIL` and `ASET` in the editor to find all these parts
* GhostParts.cfg 2.0 now included
* `disableColorPicker` = False went missing from ModuleLight, found and put back

### Create 0.9.0.0

* closes #7 - Create GitHub Pages
* closes #8 - Create HeroLogo.png
* closes #11 - Create <StackInlineLights.cfg>
* closes #32 - Create Agency

### Localization 0.9.0.0

* closes #9 - Create Localization directory and contents
* closes #13 - English <en-us.cfg>
* closes #30 - Part Localization
* updates #12 - Localization - Master

### Update  0.9.0.0

* closes #10 - Part Asset Updates
* closes #31 - Part Tags

### Status 0.9.0.0

* Issues
  * closes #2 - Stack Inline LIghts (SIL) v0.9.0.0-release `<Thank you Alexustas>` edition
  * closes #4 - 0.9.0.0 Create Legal Mumbo Jumbo
  * closes #5 - 0.9.0.0 Create Documentation
  * closes #6 - 0.9.0.0 Create Social Media Presence
  * closes #3 - duplicate

---

## Version 0.8.0.0-adoption `<Brushing off the Construction Dust>`

* >>-- adopted by [zer0Kerbal](https:github.com/zer0Kerbal) --<<

* KSP 1.7.3 and newer
* Adoption Papers
  * Send
  * Post
* gather
* verify licenses
* look for existing repo/postings

### Changelog, .version, Readme.md

* created Changelog.cfg [KERBALCHANGELOG] (.this)
* Add license field
* Add author node
* Add version naming field
* added additional fields in .version (might need to tweak urls)
* added shields to Readme.md

### Online

* create spacedock/github/curseforge/forum
* GitHub Repo
* created Forum Thread
* updated SpaceDock
* updated CKAN/NetKAN

### modernization, polish, update pass on .cfg

* large .tga -> .dds ( mb ->  mb)
* moved art to .this/Assets/
* updated texture pointers in model (original, png, dds included)
* replaced mesh = with MODEL{}
* merged in patches
* Moved standard MM patches into Patches/ folder
* removed Bulb, replaced with modulecolorchanger
* upgraded to internal automation
* automated deploy/release process
* adjusted nodes (flipped orientation as needed)
* Modernized and reformatted all part cfg files
* converted from mesh = to MODEL
* Moved models/textures into Assets/ folder
* many little updates and upgrades

---

## Version 0.7.0.0-beta `< >>>-- the pre-adoption party Beta --<<< >`

* Beta Release
* 10 Apr 2020
* Kerbal Space Program 1.7.3

* from original forum post's dropbox link
* create github repo

### organize for adoption

* folder structure
* added license(s) file(s)
* added .version file
* Readme
* automated backend
* jsons
* Changelog.md -> Kerbal Changelog Changelog.cfg
* updated Readme.md
* moved changelog into separate file

---