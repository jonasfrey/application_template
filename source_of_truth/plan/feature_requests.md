add shortcuts for 'jump to prev/next video' jump to next 'l', jump to prev 'j'  
add shortcut for play stop video 'spacebar' 

export options:

show path in export name, so that video can be exported to any location . provide variables that can be used, 
example path will look like '.gitignored/exports/{ts}_{pname}_{}'
    'ts' = n_ts_ms_now , unix timestamp of now. 
    'pname' = project name 
add an option to configure how the exported data will look like 
    group exports to : 
        - single section clips (one file per video section)
        - original video files ( video sections belonging to one file are concatenated to one file)
        - one large video  ( all video sections are concatenated to )



Player window: 
toggler 'auto zoom to file' it automatically sets the zoom to the current playing file. when the playhead enters a new different video file the zoom gets updated 

make sure the content is always visible (maybe use content fit property?)

button to reset the speed to 1x