SDP SCP for Directories
-----------------------
-----------------------

## Install for ZSH users
  * Add the sdp to $fpath for reference [https://unix.stackexchange.com/questions/33255/how-to-define-and-load-your-own-shell-function-in-zsh]
  * Make the function native to shell
	
	```
	   source ~/.zshrc
	   autoload sdp
	```

## Example
   ``` 
      sdp <Filename> <Destination Address>
   ```

## Idea behind the function
   > Tar the directory and then do ssh to host and untar it there.
  

