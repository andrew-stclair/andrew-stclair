# Shell One Liners

## Create partition file

This will create a file called `file-partition` that is 8GB in size

`sudo dd if=/dev/zero bs=1000000000 count=8 of=file-partition status=progress`
