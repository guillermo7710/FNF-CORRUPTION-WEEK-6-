For adding a song, you just have to add the folder name of your
custom song to songs.txt, inside "charts" folder.

Let's say your custom song is named "chart", this is how your
custom song folder should be looking like:

	chart-easy.json
	chart.json
	chart-hard.json
	Inst.ogg
	Voices.ogg (NOT NEEDED IF YOU DISABLED VOCALS ON YOUR CHART)
	config.json

________________________________________________________
The config.json file for now has only three arguments:
"icon", which defines the Freeplay head icon for your song, defaults to GF

"stage", this tricks the game into thinking you're playing on the said stage,
changing the stage background and even adding the camera zooms if you
set it to 'tutorial' or 'milf', defaults to Tutorial

"name", defines the name to be shown on Singleplayer/Local Multiplayer menu,
defaults to the folder name