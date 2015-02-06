# symbiosis-pieces
Bits and pieces for symbiosis. symbiosis-mysql-restore will quickly restore one (or all) databases for a Symbiosis system.


    $ ./symbiosis-mysql-restore -h
    help: ./symbiosis-mysql-restore options -dp
    
    This script restores databases backed by backup2l from /var/backups/mysql
    It is intended for use with Bytemark's Symbiosis system.
    
    OPTIONS:
       -h    Show this message
       -d    Specify a database - if none is specified, all will be restored.
       -u    Database user to use.
    
    You will be prompted for a password upon running this script. It must be
    the MySQL user's password.
