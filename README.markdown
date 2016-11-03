# A BBEdit package for working with Puppet manifests

## Installation

###For BBEdit versions before 11:
```
    $ cd ~/Library/Application\ Support/BBEdit/
    $ mkdir Packages
    $ cd Packages
    $ git clone https://github.com/kelseyhightower/puppet.bbpackage.git
```
###For BBEdit 11:
```
    $ mkdir tmp
    $ git clone https://github.com/schatt/bbedit-puppet.git
    $ cd bbedit-puppet
    $ cd ~/Library/Application\ Support/BBEdit/
    $ cp -r Contents/Clippings/Puppet ~/Library/Application\ Support/BBEdit/Clippings/Puppet
    $ cp Contents/Language\ Modules/Puppet.plist ~/Library/Application\ Support/BBEdit/Language\ Modules/Puppet.plist
```
Restart BBedit
