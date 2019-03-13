# del_as_rm
Worry about "rm -rf *"? Replace 'rm' by 'del'


A bash program feel somewhat like 'rm', but uses 'mv XXX ~/.Trash' to remove files.

If there is any file/dir have the same name as the to-be-removed file in ~/.Trash, the old file will be kept as is while a data-time postfix will be added to the new file.


## Usage

Put 'del' file in '~/bin' and make it executable:

> $ mv del ~/bin
> $ chmod +x ~/bin/del


When use

> $ del files-or-dirs-to-be-removed


## Know issues
Does not take any options other than file/dirctory names
