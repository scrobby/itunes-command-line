# iTunes Command Line
Command line tool largely based on a post by David Schlosnagle in a Macworld forum back in 2008.

I initially tried to modify this script so that I could add songs to the iCloud Music Library if they weren't already there, but it seems that Apple has not made that feature accesible via applescript. Instead I've added the option to like and unlike songs.

## Usage
### Homebrew
> iTunes Command Line is not currently available through homebrew but I'm working on it.

### Manual
- Download the 'itunes' file to your downloads folder.
- Run the following commands in terminal:

```
$ cd ~/Downloads
$ chmod u+x itunes
$ sudo mv itunes /usr/local/bin
```

- Now you've installed the itunes cli! To see all of the available commands just run ```$ itunes help```. It's fairly self-explanatory.

## To Do
- [ ] Add ability to add current song to playlist (would also have the side-effect of adding to iCloud Music Library if the option is set to true in iTunes)
- [ ] Make available through homebrew
