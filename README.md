# del_as_rm
Worry about "rm -rf *"? Use a new command 'del' to replace 'rm'

A bash program behave somewhat like 'rm', but uses 'mv XXX ~/.Trash' to remove files.


## Usage

Place the 'del' file in '~/bin'

Make it executable:
$ chmod +x ~/bin/del


## Know issues
Does not take any options other than files/dirctories
