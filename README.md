## Compress Videos & Photos Using Bash

This project demonstrates how to compress videos and images using Bash commands like tar, gzip, and xz for efficient storage.

### Features
- Archive and compress files using tar.gz, tar.xz, and zip
- Reduce storage space for videos and images
- Simple and reusable Bash commands

### Usage
*Compress a video or photo folder*

`tar -czvf compressed_files.tar.gz /path/to/videos_or_images/`

*Extract files*

`tar -xzvf compressed_files.tar.gz`

*Compress with higher compression (XZ)*

`tar -cJvf compressed_files.tar.xz /path/to/files/`

Use these commands to efficiently store and transfer large media files!

