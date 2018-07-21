# brew-unison

To keep track of unison versions in brew 

## to use

brew install unison first, then
extract unison to /usr/local/Cellar/unison/[version]

then rename and add in this required version
```
brew install unison

mv /usr/local/bin/unison /usr/local/bin/unison-bak

ln -s /usr/local/Cellar/unison/2.48.15/bin/unison /usr/local/bin/unison
```
