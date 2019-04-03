# docs

`docs` simply looks for a `.docs/` in the current directory.
If `.docs/` does not exist, it go to the parent directory and tries again.
This is repeated until `docs` either finds a `.docs/` or reaches the root directory.
A document corresponds to a file in this directory.

Usage
---

- `docs init` - create `.docs/` in current directory
- `docs list` - list all documents  
- `docs edit <FILE>...` -  edit documents  
- `docs print <FILE>...` -  print documents  
