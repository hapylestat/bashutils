ABOUT
------------

Some kind of bash library, which helps to speed-up writing a scripts 
from a scratch, implements idea of re-usable code and have a possibility
to write own modules.

Library ships with a collection of scripts to automatize some tasks in linux.


How to use 
----------

General:
   - create /etc/system.conf, example can be found in bashtools/lib/resources/
   - change libROOT variable path to place, where lib folder are located

Optional:
   - create symlink in /usr/bin for  bashtools/lib/helpers/makescript
     This allow u to create new script from template and save a time
   - blank templates are located here bashtools/lib/helpers/templates and used 
     by makescript utility

Samples:
   - Located under bashtools/_dev_system/*
   
   
   
   H.L., 2014
