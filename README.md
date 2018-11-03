# Usage

To look for duplicate files in the current directory (and subdirectories):

	find-dupes
	
To look for duplicate files in another directory, say, ~/music/2018:

	find-dupes ~/music/2018
	
To only print out the paths of files including directories, use the `--full` option.

To print out file paths escaped so that they can be directly copied and pasted back into the shell (e.g. for deleting via the command line), use the `--escape` option.

# Deleting files

If you delete files on the command line, it is recommended to use a Trash tool, rather than simply using `rm` to minimize the possibility accidentally deleting the wrong file. On Mac OS X, you can install the `trash` command via `brew install trash`.