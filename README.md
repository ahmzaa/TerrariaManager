# TerrariaManager

## What

TerrariaManager as the name suggests is a script that allows you to manage your terraria servers all from one script.

With the tool you can (so far)

- Create Servers
- Remove Servers
- Start Servers
- Quit Servers
- Restart Servers
- Install server binaries

## Why

Managing even a single Terraria server can be a hassle especially since were using the tmux option of running the server.
So having a wrapper script that allows us to do a bunch of actions will save us a lot of time.
I think the beauty of this script is when it comes to managing more than one Terraria server on a host.

## How

TerrariaManager is written in shell, I have chosen this as what I'm writing here is simply a wrapper script and shell script is super simple and easy to read / understand.
The script makes use of tmux to allow the running of multiple servers simultaneously.

## Roadmap

- [x] Server Version Control
- [ ] Check Server Status
- [ ] Default options for server creation (if user leaves blank)
- [ ] Add Logic to support using the script on MacOS / Windows / WSL

## Notes

This tool has been written and tested on Linux.
I will test using MacOS and WSL soon.
