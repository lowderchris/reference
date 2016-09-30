#VIM

Useful .vimrc settings

	set number
	set linebreak
	syntax on

Condense broken-apart lines into a single line paragraph.

	:%s/\n\([^\n]\)/\1/
