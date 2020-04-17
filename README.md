### strips

-----

*strips* is just a super simple Python script to strip line based comments from PowerShell scripts.
Nothing really dedicated, I just wanted to backup it somewhere.


### Usage

-----

```
$ python3 ./strips -h
usage: strips [-h] infile outfile

Simple utility to strip comments from a PowerShell scripts. Does only work on 'full-line'
comments. Or in other words: Lines that contain a mix of valid code and comments are not
stripped.

positional arguments:
  infile      path to the powershell script
  outfile     path to the stripped powershell script

optional arguments:
  -h, --help  show this help message and exit
```
