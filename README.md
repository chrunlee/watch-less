watch-less 监控文件夹内less文件的变化并自动编译。
==============================


## Installation

Install it as a command line tool via `npm -g`.

Depend on `less` in global.
```sh
npm install less -g
npm install watch-less -g
```

## Execution

```sh
$ watch-less
// or with directory
$ watch-less -d /home/less
// or start it with a target directory
$ watch-less -d /home/less -t /home/target
```

## Help

```sh
$ watch-less --help
Usage:
  watch-less --help // print help information
  watch-less // current directory as default
  watch-less -d /home/less // watch a directory
  watch-less -d /home/less -t /home/target // watch a directory and output to a target directory
```

## License
The MIT license.
