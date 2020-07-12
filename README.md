# del_as_rm
Worry about "rm -rf \*"? Replace 'rm' by 'del'


A bash program feel somewhat like 'rm', but uses 'mv XXX ~/.Trash' to remove files.

If there is any file/dir have the same name as the to-be-removed file in _~/.Trash_, the filename of new file will be kept as is, while a date-time postfix will be added to the filename of the old file in _~/.Trash_.


## Usage

Put 'del' file in '~/bin' and make it executable:

> $ mv del ~/bin

> $ chmod +x ~/bin/del


When in use,

> $ del files-or-dirs-to-be-removed


## Know issues
Does not take any options other than file/dirctory names
