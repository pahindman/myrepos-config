myrepos-config
======

Configuration files for myrepos

Initial Setup:
* Install git, mr, vcsh
* 'vcsh clone https://github.com/pahindman/myrepos-config'
* Copy desired repo configuration files from ~/.config/mr/available.d/ to ~/.config/mr/config.d/
* Configure ssh for use with github (e.g. ssh-add key to ssh-agent)
  * mr / vcsh use SSH rather than HTTPS to make it easy to push updates
* 'mr update'
