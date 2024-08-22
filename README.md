# crun
C-Run,
As the name suggets, this is a simple script which will compile and run .c/cpp (C/C++) files. For now this script only supports normal compilation but will be updated over time...
# Installation
Download the latest crun script from [**Here**](https://github.com/xxrishikcooIN/crun/releases) and run 
```
sh crun --install
Note: Users Will Be Asked To Choose An Edition(Full,Slim,Core) Of crun.sh
```
# Usage
```
Usage: crun <filename> [options] [target] ...
/*Note: For C++ Files: Usage: crun <filename> [g++ options] ...} - Preview Of C++ Compilation Support In crun.sh

Options: (Script Specific)

  --update    : Download and install the latest version of crun available online (wget is required).
  --rm-old    : Delete previously cached compiled-binaries in the working directory.
  --uninstall : Uninstall crun.sh.
  --help      : Print this message and exit.
  --version   : Print the version number of crun and exit.

And all other 'make' options mentioned above as [options] [target] ...
```
# Supported Operating Systems
Only Linux And macOS Are Currently Supported
# Note
Core Edition Cannot Be Updated Through The Installed Script As Script-Updater Will Be De-Bloated Alongside Other Script-Specific-Code
