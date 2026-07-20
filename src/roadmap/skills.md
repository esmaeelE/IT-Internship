# IT Skills Roadmap

Track your progress with checkboxes. Check items as you complete them.

## General Skills
- [ ] **Typing**: 10-finger typing, aim for 40+ WPM — [MonkeyType](https://monkeytype.com), [keybr](https://keybr.com)
- [ ] **Search**
    - Use search engines effectively — select correct keywords, use operators (`site:`, `filetype:`, `-`)
    - Read official documentation and man pages before Googling
- [ ] **Communication**
    - Be cool in office — ask clear questions, document answers
    - Give back, not just get — share knowledge, write notes others can use
- [ ] **Community**: contribute to open source, forums, or local meetups to expand knowledge and experience
- [ ] **English**: daily reading/writing — docs, Stack Overflow, news (Hacker News, Ars Technica)
- [ ] **Time management & Planning**: daily notes, weekly reviews, break tasks into small pieces
- [ ] **Documentation**: write it down — your future self will thank you
- [ ] **Build a solid IT background**
    - [Computer Basics پایه‌های رایانش](https://peertube.linuxrocks.online/c/computing_basics/videos?s=1)
    - Learn material in depth, not surface-level
    - Avoid technical debt from the first steps

## Operating Systems

### GNU/Linux (primary)
- [ ] Install a real distro (Debian, Arch, Fedora) — not a toy
- [ ] Learn the CLI, package management, file system hierarchy
- [ ] Shell scripting basics
- [ ] [Ryan's Linux Tutorial](https://ryanstutorials.net/linuxtutorial/) — free, structured course
- [ ] [The Linux Command Line](https://linuxcommand.org/tlcl.php) — free book

### Windows
- [ ] Clean install — remove bloatware, disable auto-update, configure privacy
- [ ] WSL2 as escape from Windows hell
    - Virtualization basics, Debian on WSL, tmux, dev environment setup
    - [WSL Docs](https://github.com/MicrosoftDocs/WSL/tree/main)
- [ ] Overview of special-purpose OS: RTOS, embedded Linux, FreeBSD

## Programming

### Python
- [ ] [Python Basics](https://pythonbasics.org)
- [ ] [Automate the Boring Stuff](https://automatetheboringstuff.com) — free, practical
- [ ] Practice: write small scripts daily — file processing, web scraping, CLI tools

### C (recommended next)
- [ ] [Beej's Guide to C](https://beej.us/guide/bgc/) — free, comprehensive
- [ ] Understand pointers, memory, compilation — this is how computers actually work

### Algorithms & Data Structures
- [ ] [VisuAlgo](https://visualgo.net) — visualize sorting, trees, graphs
- [ ] [Big-O Cheat Sheet](https://www.bigocheatsheet.com)
- [ ] Start with: arrays, linked lists, hash maps, binary search, basic sorting

### Programming Paradigms
- [ ] Quick review: Procedural → Functional → Object-Oriented
- [ ] Learn *why* each exists, not just syntax

## Text Editors

### Vim / Neovim
- [ ] Learn basic Vim motions: `h j k l`, `i`, `Escape`, `:wq`, `dd`, `yy`, `p`
- [ ] Work through `vimtutor` (run `vimtutor` in terminal)
- [ ] Gradually add a config — start minimal, grow as needed

## CLI Tools

Essential Unix tools for daily work:

- [ ] `grep` — search text in files
- [ ] `awk` — text processing and column extraction
- [ ] `sed` — stream editor, find and replace
- [ ] `jq` — parse and query JSON from terminal
- [ ] `find` / `locate` — find files on the system
- [ ] `curl` / `wget` — download files, test APIs
- [ ] `tmux` — terminal multiplexer, persist sessions
- [ ] `ssh` — remote access to servers

> **Tip**: Learn one tool per week. Use it in real tasks. Force yourself.

## Git
- [ ] [Pro Git Book](https://git-scm.com/book/en/v2) — free, essential
- [ ] Daily workflow: `git add`, `git commit`, `git push`, `git branch`, `git merge`
- [ ] Learn branching strategy early (feature branches)

## Networking
- [ ] OSI model basics, TCP/IP, HTTP/HTTPS
- [ ] `ping`, `curl`, `netstat`, `ss`, `tcpdump`
- [ ] [Computer Networking: A Top-Down Approach](https://gaia.cs.umass.edu/kurose_ross/online_lectures.htm) — free lectures

## Databases
- [ ] SQL fundamentals — SELECT, JOIN, indexes
- [ ] [SQLBolt](https://sqlbolt.com) — interactive SQL tutorial
- [ ] Know the difference: relational (PostgreSQL, SQLite) vs. NoSQL (Redis, MongoDB)

## Containers & DevOps Basics

### Docker
- [ ] What containers are vs. VMs — the mental model
- [ ] `docker run`, `docker ps`, `docker stop`, `docker rm`
- [ ] Write a `Dockerfile` for a Python app
- [ ] `docker-compose` for multi-service apps
- [ ] [Docker Getting Started](https://docs.docker.com/get-started/)

### SSH
- [ ] Generate SSH keys: `ssh-keygen`
- [ ] Connect to remote servers: `ssh user@host`
- [ ] Copy files: `scp` or `rsync`
- [ ] Configure `~/.ssh/config` for shortcuts

