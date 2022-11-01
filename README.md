![bash_unit CI](https://github.com/pforret/rpi_dashboard/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/rpi_dashboard/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/rpi_dashboard)
![GH stars](https://img.shields.io/github/stars/pforret/rpi_dashboard)
![GH tag](https://img.shields.io/github/v/tag/pforret/rpi_dashboard)
![GH License](https://img.shields.io/github/license/pforret/rpi_dashboard)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://www.basher.it/package/)

# rpi_dashboard

Dahsboard with rotating pages on Raspberry Pi

## 🔥 Usage

```
Program: rpi_dashboard 0.0.1 by peter@forret.com
Updated: 2022-11-01
Description: Dahsboard with rotating pages on Raspberry Pi
Usage: normal.sh [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] <action> <input?>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] output more [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/normal]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: .tmp]
    <action>         : [parameter] action to perform: analyze/convert
    <input>          : [parameter] input file/text (optional)
```

## ⚡️ Examples

```bash
> rpi_dashboard .
# start PhpStorm with current folder as project
```

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/rpi_dashboard

or with `git`

	$ git clone https://github.com/pforret/rpi_dashboard.git
	$ cd rpi_dashboard

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2022 Peter Forret
