Prerequisite
============

1. `sudo pip install shell`
2. install google python search.  https://github.com/MarioVilas/google

Run
===
I use google to search first 1000 sites and try to get the `/etc/passwd`
After tesing, there are many many many host that can be rooted!!!!
By the way, this is only a proto, it has false positives.

Output like this:
if second field is `!!!`, then You Can Get SHELL!

```
$ python shellshock.py
0 --- http://nomad3.ncep.noaa.gov/cgi-bin/pdisp_sst.sh
1 --- http://nomad5.ncep.noaa.gov/cgi-bin/pdisp_gfs.sh?ctlfile=gfs_00z.ctl&povlp=noovlp&ptype=map&dir
```

References
===========
http://vonnyfly.github.io/

https://www.invisiblethreat.ca/2014/09/cve-2014-6271/
