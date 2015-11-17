# Download Github Gists

> A PHP script for downloading all of a users Github gists.

## Install

```
$ curl https://raw.githubusercontent.com/kjbrum/download-github-gists/master/download-gists > ~/bin/download-gists
$ chmod +x ~/bin/download-gists
```

## Usage

```
Download all of a users gists from Github.

Usage:
    download-gists <username>
    download-gists <username>:<password>
    download-gists <username> ./
    download-gists <username>:<password> ./

Arguments:
    username:password    The username for getting gists. You can optionally add the password to get secret gists
    location             Location to save the gists (Default: ~/Downloads/gists)\n\n";
```

## License

Copyright © [Kyle Brumm](http://kylebrumm.com). Free to use on whatever and may be redistributed under the terms specified in the [license](LICENSE.md).
