# videoStreamCreator
 Creates video stream for icecast server from movie files in folder.
 
 This will loop over all files found in the mounted directory and any subfolders within.
 
## Path
- Video Storage Directory: /videos

## Environmental Variables
- ICECAST_SERVER
- ICECAST_PORT
- ICECAST_SOURCE_SECRET
- ICECAST_MOUNT - A .TS extension will be added for the stream

NOTE: All video files must be the same format
NOTE: The looping process presently requires the player to automatically reconnect