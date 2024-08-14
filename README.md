# compare
Compare two files on a GNU/Linux system to verify if they are identical or not.

```
sha256sum file_1.txt
sha256sum file_2.txt
```

Only use `sha256sum`. Do not use `sha1sum` or `md5sum`.


Spaces can be escaped with a backslash:

```
sha256sum file\ 3.txt
```


Links:
- https://www.baeldung.com/linux/fastest-check-files-same-content
- https://unix.stackexchange.com/questions/260513/diffference-between-sha1sum-sha256sum-and-md5sum
- https://askubuntu.com/questions/172947/what-are-the-differences-between-md5sum-and-sha256sum

