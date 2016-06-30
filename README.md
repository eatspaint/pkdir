# pkdir
![example image](http://eatspaint.com/pkdir_example.png)
#### Install: 
In your terminal, run `brew tap eatspaint/pkdir; brew install pkdir`

For updates, run `brew update` and then `brew upgrade pkdir`
#### Usage: 
Use `pkdir` just as you would use `mkdir`, but get Pokémon instead of boring folder icons.
```
pkdir <name> [-n]
```
`<name>` can be a new directory, or an existing file or directory
`[-n]` is an optional 3 digit flag to select a specific pokémon, by number

You can also run `pkdir -h` for help with commands.
#### Example:
```
pkdir ~/Desktop/my_folder -006
```
Wow, there's a cool Pokémon on my desktop, thanks eatspaint!

#### System Requirements:
Because of the fileicon bash script used, this project is currently OSX only. If anyone is interested in getting this running for Linux as well, let me know and we can collaborate on a solution!
***
Thanks to [mklement0](https://github.com/mklement0) for [fileicon](https://github.com/mklement0/fileicon), DragonFlyCave for the [sprites](http://www.dragonflycave.com/sprites.aspx), and Pokémon for my childhood.
