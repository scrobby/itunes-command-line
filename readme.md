# iTunes Command Line
Command line tool largely based on a post by David Schlosnagle in a Macworld forum back in 2008.

I initially tried to modify this script so that I could add songs to the iCloud Music Library if they weren't already there, but it seems that Apple has not made that feature accesible via applescript. Instead I've added the option to like and unlike songs.

## Usage
Installation is as simple as adding the "itunes" file to your $PATH and making sure it's executable. If you want instructions on how to do that, I found this post very useful: http://ss64.com/osx/syntax-shellscript.html
> *If anyone has a way of doing this that is more efficient/better practice then please let me know - I'm not hugely experienced in bash scripts!*

To see all of the available commands just type "itunes help". It's fairly self-explanatory.

## To Do
- [ ] Add ability to add current song to playlist (would also have the side-effect of adding to iCloud Music Library if the option is set to true in iTunes)
- [ ] Make available through homebrew
