# pyacme

A python wrapper around plan9port's `9p` command. Makes it easy to write
python scripts that interact with Acme.

Russ Cox's [video](https://www.youtube.com/watch?v=dP1xVpMPn8M) is
an excellent introduction to Acme.

## Usage

```
#!/usr/bin/python

import pyacme

winid = pyacme.windownew() # creates a new window
writectl(winid, "clean") # mark window as 'clean'
writebody(winid, "This is an example\n") # write to the window's body
```

## TODO

- Write to all 'files' in `/mnt/acme/`
- Read from all 'files' in `/mnt/acme/`
