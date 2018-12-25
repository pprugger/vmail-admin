# vmail-admin
CLI Tool for managing vmail databases

`vmail-admin` is a command line tool for managing a mail-server database
based on the great [HowTo](https://thomas-leister.de/en/mailserver-debian-stretch) ([german version](https://thomas-leister.de/mailserver-debian-stretch/))
from [Thomas Leister](https://thomas-leister.de) written in Bash.

## Prerequisites

Make sure you have a working setup as described in the tutorial as `vmail-admin`
relies on the described database scheme (MySQL or MariaDB).

Further, as `vmail-admin` is written in Bash, you should have bash installed.

# Installation

* Download vmail-admin.sh from github.
* Make it executable with "chmod +x vmail-admin.sh".
* Run it with "./vmail-admin.sh".

# Usage

You can change the parameters for the script under Definitions in the script.
Start the script with:
```shell
./vmail-admin.sh
```

## Main Menu

Menu items are:
1. User Management
2. Domain Management
3. Aliases Management
4. Database Management
5. Exit
