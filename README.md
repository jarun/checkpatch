# checkpatch
Copy of checkpatch from [torvalds/linux/scripts](https://github.com/torvalds/linux/tree/master/scripts)

To update the files, run any of the following commands:

    wget -i files
    aria2c -i files --allow-overwrite=true

To run on your own file (not in a regular linux kernel tree):

    checkpatch.pl -f --no-tree your_file.c
