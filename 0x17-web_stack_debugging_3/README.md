# Web Stack Debugging #3

This was the fourth in a series of web stack debugging projects. In these projects, I was given broken/bugged webstacks in isolated containers, and tasked with fixing the web stacj to a working state. For each task, I wrote a short script automating the commands necessary to fix the stack.

## Tasks

### 0. Strace is your friend
- **[0-strace_is_your_friend.pp](0-strace_is_your_friend.pp)**: Puppet manifest that fixes an issue causing a WordPress application being served by an Apache web server to fail.
- **Usage**: `puppet apply 0-strace_is_your_friend.pp`
