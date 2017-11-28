watchlessc 监控文件夹内less文件的变化并自动编译。
==============================


## Installation

Install it as a command line tool via `npm -g`.

Depend on `less` in global.
```sh
npm install less -g
npm install watchlessc -g
```

## Execution

```sh
$ watchlessc
// or with directory
$ watchlessc -d /home/less
// or start it with a target directory
$ watchlessc -d /home/less -t /home/target
```

## Help

```sh
$ watchlessc --help
Usage:
  watchlessc --help // print help information
  watchlessc // current directory as default
  watchlessc -d /home/less // watch a directory
  watchlessc -d /home/less -t /home/target // watch a directory and output to a target directory
```

## License
The MIT license.
