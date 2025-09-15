# Networking Basics #1

Welcome to the second networking project at Holberton School. This project builds on what you’ve learned in “Networking basics #0” and focuses on hands-on networking tasks using basic Bash scripting.

## 🚀 Project Overview

This project is an introduction to manual IP resolution, local interface exploration, and TCP port listening. It helps reinforce how machines communicate over a network — even when just using `localhost`.

## 🎯 Learning Objectives

By completing this project, you will be able to:

- Understand and modify the `/etc/hosts` file
- Display all active IPv4 addresses on your machine
- Listen on a specific TCP port using `netcat`
- Use `telnet` to test local TCP connections
- Automate network interactions using Bash scripting

## 📂 Tasks

### 0. Change your home IP

Write a Bash script that updates the `/etc/hosts` file so that:
- `localhost` resolves to `127.0.0.2`
- `facebook.com` resolves to `8.8.8.8`

This simulates overriding domain resolution for testing purposes.

### 1. Show attached IPs

Write a Bash script that displays all active **IPv4** addresses of the machine it’s run on. Only IPv4 addresses should be shown, one per line.

### 2. Port listening on localhost

Write a Bash script that listens on TCP **port 98** of `localhost` using `netcat`. It should display any text received on that port.

---

## 🛠️ Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- Files interpreted on Ubuntu 22.04 LTS
- All scripts must end with a new line
- A `README.md` file is mandatory at the root of the project
- All Bash scripts must be executable
- Scripts must pass Shellcheck (v0.7.0) without errors
- First line of each Bash script must be: `#!/usr/bin/env bash`
- Second line must be a comment explaining what the script does