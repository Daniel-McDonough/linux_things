# Random Linux Commands


Cut video file at specific times: `ffmpeg  -i input.mp4 -ss 00:00:00 -to 00:00:00 -c copy out.mp4`

Mount NFS: `sudo mount -t nfs4 -o proto=tcp,port=2049 $ADDRESS:/ /mnt/path`

Transfer Files with Bandwidth Limit: `rsync --progress -av --bwlimit=60000k --remove-source-files`


