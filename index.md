## About VRL

VRL is the author of vrl-package, owner of vrl.sh domain and Founder of the VRL Community Discord

Quick links:
- [vrl-package Gitlab](https://gitlab.com/vrl/vrl-package)
- [https://about.vrl.sh/](https://about.vrl.sh/)
- [VRL Community Discord](http://d.vrl.sh)


# Basic vrl-package rundown

![Unable to load remote image](https://github.com/vrlnx/vrlnx/blob/gh-pages/media/Pasted%20image%2020210828003002.png)

```bash
# vrl-package comes with some commands

$ vrl help
$ vrl start
$ vrl follow
$ vrl stop
```

### $ vrl start
`vrl start` starts BYOB and threads the BYOB program in background so you can still use the terminal to achive other tasks.

BYOB's web-gui will open on you local network and will be reachable from anywhere on your local network. To see your local and external IP type `vrl help`

### $ vrl stop
`vrl stop`stops ongoing BYOB thread, this command is nice if BYOB crashes. You can then quickly start BYOB again using `vrl start`.

### $ vrl follow
`vrl follow`tails the log ongoing in the BYOB thread, this command is nice if you want to monitor your BYOB instanse.

### $ vrl help
`vrl help` is the vrl-package's own help command, `vrl help` shows other commands vrl-package offers, along with your local and public IP.

### Support or Contact

Having trouble with vrl-package? Check out our [documentation](https://gitlab.com/vrl/vrl-package/-/wikis/home) or [create a support ticket in Discord](http://d.vrl.sh) and we’ll help you sort it out.
