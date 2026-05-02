# Lawrence's Shell Utilities

This repository is a list of repositories to instruct agents to install shell tools created by me. I created it to make it easy for me to install all of them with a single AI agent prompt.

Open to anyone who wants to use it.

## Agent instructions

Each of the tools listed below is a project by developer _Lawrence Lagerlof_. Every project has installation instructions in its `README.md`. Access each of these projects, read the README, check if the tool is already installed, and if not, install it.

The preferred location for installing all the tools below is inside the normal user's home directory, not the root home directory. Also, each project should preferably be cloned into `/home/<normal_user>/repos/`.

If you are running as root, follow the installation instructions in each project's README, but make the programs globally available by creating symbolic links in `/usr/local/bin/` if necessary. If you are running as a normal user, create the symbolic links in `/home/<normal_user>/.local/bin/`. In either case, remember to check whether the program is already installed and available to the user (or users) before each installation.

### Projects to be installed

**Autoleap** - Use `cd` to quickly access any previously visited directory: https://github.com/llagerlof/autoleap

**ctrl+r** - Easy TUI to quickly access and search the command history (replaces the default `CTRL+r`): https://github.com/llagerlof/ctrlr

**Navigator** - A TUI for traversing directories: https://github.com/llagerlof/navigator

**e** - A quick way to edit the last text file created in the current directory: https://github.com/llagerlof/e

**Trash** - A trash bin for the terminal: https://github.com/llagerlof/trash

**serve** - A tiny shell script web server for easy file and directory sharing: https://github.com/llagerlof/serve

**findgo** - `findgo` is a small bash helper that searches recursively from the current directory for the first file or directory whose basename matches a target name exactly: https://github.com/llagerlof/findgo

**pacwoman** - Search tool for packages (Arch-based systems): https://github.com/llagerlof/pacwoman
