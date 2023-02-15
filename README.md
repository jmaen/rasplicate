<p align="center">
  <img src="https://user-images.githubusercontent.com/47495425/213450723-f984b125-caef-49b5-aab6-92857062aa17.png" width=100 height=100/>
</p>


# rasplicate
**rasplicate** is a tool that turns your Raspberry Pi into an automatic backup server.

## Config
- source
- destination
- interval
- file change threshold (e.g. >5%) -> warning
- GPIO status lights (backup - idle - warning)
- in-/excludes

## Sources
- [rdiff-backup usage](https://rdiff-backup.net/examples.html)
- [Unattended backups](http://arctic.org/~dean/rdiff-backup/unattended.html)
