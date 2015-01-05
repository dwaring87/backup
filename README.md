Mac OS X Backup Utility
=======================

For more information and a GUI program for Mac OS X visit: [http://www.davidwaring.net/projects/backup.html](http://www.davidwaring.net/projects/backup.html)

This project started out as a simple shell script wrapper for [rsync](https://rsync.samba.org/). rsync is a great tool for performing backups since it will sync all files from a source location to a destination directory while keeping most of their privileges and extended attributes intact. The most convenient feature of rsync is that after the first backup, it will only sync the files that have changed, greatly reducing the amount of time required to perform a backup. This program was originally written to perform a backup of my laptop's internal hard drive to an external drive with the ability to "bless" the backup to make it bootable. The project has expanded from just a shell script to include a GUI wrapper for the shell script that can handle multiple backup configurations.
