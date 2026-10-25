FROST PLUGIN v3.0 - Paper 1.21.11 / Java 21

NO RESOURCE PACK REQUIRED. Remove the old resource-pack URL and disable the client resource pack.

Changes:
- Frost item models restored to vanilla; old gear cleaned on join, or /frost cleartextures.
- All custom ability damage uses armor/enchantment-bypassing vanilla sonic-boom damage,
  with damage sounds and ordinary Totem of Undying compatibility.
- Crossbow Warden Shriek deals 8 health points = 4 hearts (before Resistance),
  and no longer applies any Slowness to the shooter.
- Frozen Horn summons Strays with Sharpness IV + Curse of Vanishing diamond swords
  and unbreakable iron helmets, targeting untrusted players only.
- Passive snowflake particles appear around any player carrying or wearing Frost items.
- /frost config includes a particle-effects section.
- /frost weapons GUI remains OP-only.

Upload the contents of this folder to the ROOT of your GitHub repository, not as
a nested directory. GitHub Actions build.yml is in .github/workflows/build.yml.

The compiled JAR belongs in the Paper server plugins/ folder.
After installation, /frost cleartextures also cleans old items from earlier versions.
Existing plugins/PunchSnowball/config.yml and trusted.yml should be preserved.
