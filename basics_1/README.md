# Networking basics #1

Project on localhost, 0.0.0.0, the `/etc/hosts` file, and inspecting network interfaces and listening ports.

## Resources

**Read or watch:**
- What is localhost
- What is 0.0.0.0
- What is the hosts file
- Netcat examples

**man or help:**
- `ifconfig`
- `telnet`
- `nc`
- `cut`

## Learning Objectives

At the end of this project, you should be able to explain, without the help of Google:

- What is localhost / 127.0.0.1
- What is 0.0.0.0
- What is `/etc/hosts`
- How to display your machine's active network interfaces

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- All files are interpreted on Ubuntu 22.04
- All files end with a new line
- A `README.md` file at the root of the project folder is mandatory
- All Bash scripts must be executable
- Bash scripts must pass `shellcheck` (version 0.7.0 via `apt-get`) without any errors
- The first line of every Bash script is exactly `#!/usr/bin/env bash`
- The second line of every Bash script is a comment explaining what the script does

## Tasks

| # | Task | File | Points |
|---|------|------|--------|
| 0 | Change your home IP | `0-change_your_home_IP` | 2 |
| 1 | Show attached IPs | | 1 |
| 2 | Port listening on localhost | | |

### 0. Change your home IP

Bash script that configures an Ubuntu server so that:
- `localhost` resolves to `127.0.0.2`
- `facebook.com` resolves to `8.8.8.8`

Run it with `sudo`, since it edits system files.

> If you run this on a machine you keep using, revert `localhost` to `127.0.0.1` afterwards, otherwise many things will stop working.

## Repository

- GitHub repository: `holbertonschool-network`
- Directory: `basics_1`

## Author

  Rahaf Alabdalh 
