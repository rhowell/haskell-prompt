# Haskell Prompt

This is a daemon for Mac OS X and Linux.  It is responsible for tracking anything that may be of interest to a user of the console.  This service will return a properly formatted ```PS1``` variable for the current directory.


### Eventually...
Hopefully this will be configurble on a per-directory basis.  Meaning, different directories or groups of directories will support different prompts.  I'm planning various strategies for how to determine which prompt to use. 

	* By directory wildcard
	* By language of current project
	* By current source control system (git, darcs, etc...)

	
