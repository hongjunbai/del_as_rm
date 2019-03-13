# del_as_rm
Worry about "rm -rf *"? Replace 'rm' by 'del'

A bash program feel somewhat like 'rm', but uses 'mv XXX ~/.Trash' to remove files.


## Usage

Put 'del' file in '~/bin' and make it executable:

$ mv del ~/bin

$ chmod +x ~/bin/del


When use

$ del 'files-dirs-to-be-removed'


## Know issues
Does not take any options other than file/dirctory names
