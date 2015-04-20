# ascope
Another cscope front end for emacs
Usage:
	load this script using (require 'ascope.el) in you .emacs
	M-x ascope-init load the cscope database. This command must be issue prior to issue any other command blew, the directory feed to this command must be the directory include the cscope.out file
	M-x ascope-find-global-definition
	M-x ascope-find-this-symbol
	M-x ascope-find-this-text-string
	M-x ascope-find-functions-calling-this-function
	M-x ascope-find-called-functions
	M-x ascope-find-files-including-file
	M-x ascope-all-symbol-assignments
	M-x ascope-clear-overlay-arrow
	M-x ascope-pop-mark
