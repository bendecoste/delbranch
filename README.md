delbranch
=========

Deletes git branches matching a pattern

### Usage

```bash
~/Documents/delbranch master: git branch
  bendecoste-example
  bendecoste-example2
* master
  otherdude
~/Documents/delbranch master: delbranch bendecoste
Deleted branch bendecoste-example (was 9b820d6).
Deleted branch bendecoste-example2 (was 9b820d6).
~/Documents/delbranch master: git branch
* master
  otherdude
~/Documents/delbranch master:
```
