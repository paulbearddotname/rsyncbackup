# rsyncbackup

rsyncbackup is a backup program capable of creating backup directories that mirror the source without duplicating unmodified files.

Each run results in a new backup directory named with the date and time the backup started.
Each backup directory is a complete mirror of the source.
Unmodified backup files are hard linked.

Faster but less space efficient than [lnbackup](../../../lnbackup).

## See also

[lnbackup](../../../lnbackup)

## Website

http://paulbeard.name

## Install

    sudo install rsyncbackup /usr/local/bin/
