# renovate_issue_update
This repository is only for test purposes.
There are only two repositories defined:
* roave/psr-container-doctrine (wants doctrine/annotations version 1) 
* friendsofphp/php-cs-fixer (current version als targets doctrine/annotations version 1, but php-cs-fixer 3.16.0 targets doctrine/annotations version 2)

If you try to update php-cs-fixer to > 3.16 it won't happen, because roave/psr-container-doctrine wants doctrine/annotations 1
