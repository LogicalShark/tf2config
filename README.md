# TF2 config files
Partially adapted from https://github.com/tsumo/tf2configs/blob/master/README.md, most useful are autoexec (performance optimizations), defaults (resets binds when switching classes), engineer and medic (actual significant gameplay use). cfg files go in `steamapps\common\Team Fortress 2\tf\cfg`

[Detailed explanation of why and how to use custom captions](https://www.reddit.com/r/truetf2/comments/1b4ek1g/unofficial_guide_to_captions_in_tf2_aka_automatic/), closecaption_english files do not go in the config folder, they replace files in `steamapps\common\Team Fortress 2\tf\resource` (make sure to delete any caption files in custom HUD)

I use m0rehud custom HUD with these changes: 
- moved the players alive/dead status bar to the lower half of screen  to check easier (TeamStatus attribute in the .res files)
- increased size of target health cross and hp number for better visual clarity on medic (TargetID attributes in .res files)
- replaced captions for more useful information
