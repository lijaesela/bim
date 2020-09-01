# bim (bash vim)
bim is a surprisingly cool text editor written in pure bash.  

bim aims to behave as closely to vim as possible, only departing from this behaviour when there are limitations, or if it can gain benefits from being a shell script.  

bim is extraordinarily extensible for anyone who can write basic or advanced bash scripts alike.

### using bim
clone the repository, cd into the repository, and run:
```shell
./bim --help
```
this outlines all flags and basic invocation of the command.  
to print a table of defaults for basic usage without configuration:
```shell
./bim --keys
```
vim users should get the hang of it with relative ease.  
of course, to actually run the thing:
```shell
./bim
```
now if, for whatever reason, you feel the need to become a power user of this silly little program:
```shell
./bim --rcdoc
```
this command will give you information on scripting new functionality with an rc file.
### installing bim
it's just a shell script, invoke it however you wish. :)
