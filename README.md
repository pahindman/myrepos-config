myrepos-config
======

Configuration files for myrepos

Initial Setup:
* Install git, mr, vcsh
* Configure ssh for use with github (e.g. ssh-add key to ssh-agent)
  * I use SSH rather than HTTPS with mr/vcsh to make it easy to push updates
  * It should be possible to use HTTPS for fetch and SSH for push, but it would probably make the config more complicated.
* `vcsh clone ssh://git@github.com/pahindman/myrepos-config.git`
* Copy desired repo configuration files from ~/.config/mr/available.d/ to ~/.config/mr/config.d/
* `mr update`
