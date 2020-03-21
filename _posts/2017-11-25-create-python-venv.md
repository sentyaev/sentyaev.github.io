---
layout: post
title:  "Configure Python virtual environment"
date:   2017-11-25T11:26:30+01:00
categories: python
---

### Create Virtual Environment
Assume you'd like to create venv in `~/dev/env/py3`
```bash
mkdir -p ~/dev/env/py3
python3 -m venv ~/dev/env/py3
```

To activate venv
```bash
source ~/dev/env/py3/bin/activate
```

To deactivate
```bash
deactivate
```
