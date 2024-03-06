# fzstd

Fuzzy find using `fzf` to search a string from `STDIN` and open `vim` at the right line.

Useful to find a search term and immediately get the surrounding context without using grep -A -B.

Example usage: 

```
hashcat.bin --help | fzstd
```

Requires fzf and vim

![](https://github.com/doomerhunter/fzstd/blob/main/fzstd.gif)
