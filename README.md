# zsdl

[zippyshare.com](http://zippyshare.com) downloader written in python

## Prerequisites

```
$ pip install requests
```

## Usage

Show help text:

```
$ ./zsdl.py --help

zippyshare.com downloader written in python
Source: https://github.com/dennisbruner/zsdl

Usage:
  ./zsdl.py <links>...
  ./zsdl.py -h | --help

Options:
  -h --help           Show this screen.
  -d --dir=<target>   Target directory where to save files [default: .].
```

Download file:

```
$ ./zsdl.py http://www123.zippyshare.com/v/...

Fetching information...
Downloading "..." (10.00 MB)...
Download done!
```

## License

[MIT](LICENSE.md)