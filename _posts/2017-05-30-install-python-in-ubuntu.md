---
layout: post
title:  "Install Python from source in Ubuntu"
date:   2017-05-30T11:26:30+01:00
categories: python
---

### Install Python 3.6

To install python in ubunty first of all you need to install prerequisites.
```bash
$ sudo apt-get install build-essential checkinstall
$ sudo apt-get install libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev
```

Then you need to download Python and extract downloaded package.
```bash
$ cd /usr/src
$ sudo wget https://www.python.org/ftp/python/3.6.2/Python-3.6.2.tgz
$ sudo tar xzf Python-3.6.2.tgz
```

Next step is compile Python source.
```bash
$ cd Python-3.6.2
$ sudo ./configure
$ sudo make altinstall
```

And finally check python version.
```bash
python3.6 --version
```
