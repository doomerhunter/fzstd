# fzstd

Fuzzy find using `fzf` to search a string from `STDIN` and open your favorite editor at the right line.

Useful to find a search term and immediately get the surrounding context without using grep -A -B.

Example usage: 

```
hashcat.bin --help | fzstd
```

Requires fzf and vim (or another editor, referenced by the `EDITOR` environment variable).

![](https://github.com/doomerhunter/fzstd/blob/main/fzstd.gif)
