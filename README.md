# rsyncbackup

rsyncbackup is a backup program capable of creating backup directories that mirror the source without duplicating unmodified files.

Each run results in a new backup directory named with the date and time the backup started.
Each backup directory is a complete mirror of the source.
Unmodified backup files are hard linked.

## Website

https://paulbeard.name

## Install

    sudo install rsyncbackup /usr/local/bin/

## Help

    $ rsyncbackup -h
    rsyncbackup version 1.2.0
    Copyright (c) 2025 Paul Beard.
    Website: paulbeard.name

    rsyncbackup is a backup program capable of creating backup directories that mirror the source without duplicating unmodified files.

    Usage: /usr/local/bin/rsyncbackup [-h] SRC_FROM DEST

    Options:
    -h       show this help
    SRC_FROM read source list from file
    DEST     destination directory
