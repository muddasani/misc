# Amiga Emulation with FS-UAE

* Log in to OAGD / Open Retro on FS-UAE Launcher to gain access to the many
database entries for Amiga games with their associated downloads.
* It does not appear to be possible to delete game entries in FS-UAE Launcher
because changes made to the local .ini file and SQLite database will be
updated on next login from the server. However, if you delete local floppy disk
images containing a certain game and need to restore them, put them in the
FS-UAE downloads directory and do Update File Database.
* Install Kickstart ROMs for better compatibility. The replacement ROM can
only go so far. In particular, for gaming, 1.3 and 3.1, I was once told, are
especially important.
* The Amiga 500 was the most popular of the series. It's a sensible default
for settings and searches for documentation.
* FS-UAE Launcher actually includes a save disk for each configuration so you
don't have to set your own up, assuming everything can fit on it. To use it,
hit F12 and use one of the empty slots under Removable Media. (N.b. there has
to *be* an empty slot in the first place. If your game uses two floppies then
you need to add at least one more floppy drive to use this feature.)
* If the floppy sounds annoy you, you can turn those off in the full settings
menu.
* Clean Up and Snapshot are useful features of the Amiga Workbench for
arranging icons. (Hint: right click with window in question focused and
navigate to menu.) Clean Up will arrange the icons into a grid and Snapshot
will "freeze" the current position of icons.
* Screenshot directory can be changed in Advanced Setting in FS-UAE Launcher
with, say, `screenshots_output_dir = ~/Pictures`.
* `joystick_port_1 = nothing` needs to be in settings for the cursor keys to
function properly. This is recommended to be used on a per-config basis only,
not globally.
* The default color palette in Workbench is ugly. On Workbench 2.1, at least,
this can be changed by going into Colors under Tools and using the following
palette: EEE, 898, 131, 282 for a nice green theme. Something similar can be
done in 3.1 by going to Prefs and then Palette but here decimal RGB triplets
are used: (238, 238, 238), (136, 153, 136), (17, 51, 17), (34, 136, 34). (It
appears necessary to shut down Workbench to save these changes though I'm
not sure? Don't want to have to experiment and set the colors up all over
again.)
* Populous appears not to cooperate well with any version of Workbench and
should just be run on its own; the same may be true of other games.
* Consider installing ClassicWB? (What are the advantages?) 