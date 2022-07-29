# ImportExportJSONDB

Usage: basic [options] [[--] args]\
   or: basic [options]

This program supports Export and Import JSON FILE From or To DB.

    -h, --help            show this help message and exit

Basic options\
    -e, --export          Export JSON File From DB\
    -i, --import          Import JSON File Into DB\
    -d, --delete          Delete Rows(Same AccounUID Exists) of DB\
    -p, --print           Print all columns From Tables Where Same AccountUID Exists\
    -s, --source=<str>    Source DB connectionstring or Source jsonfile name\
    -t, --target=<str>    Target jsonfile name or Target DB connectionstring\
    -u, --uid=<str>       Target AccountUID\
    -v, --verbosse        Provides additional details

ex) -e -u 100000000 -s connecttionstring -t jsonfilename\
ex) -i -u 100000000 -s jsonfilename -t connecttionstring\
ex) -d -u 100000000 -t connecttionstring\
ex) -p -u 100000000 -t connecttionstring
