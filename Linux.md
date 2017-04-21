# Linux

## Linux: Find Out Which Process Is Listening Upon a Port
[https://www.cyberciti.biz/faq/what-process-has-open-linux-port/](https://www.cyberciti.biz/faq/what-process-has-open-linux-port/)

```bash
# netstat -tulpn
```

## How to Compress and Extract Files Using the tar Command on Linux

Source: [https://www.howtogeek.com/248780/how-to-compress-and-extract-files-using-the-tar-command-on-linux/](https://www.howtogeek.com/248780/how-to-compress-and-extract-files-using-the-tar-command-on-linux/)

### Compress an Entire Directory or a Single File

```bash
tar -czvf name-of-archive.tar.gz /path/to/directory-or-file
```

Here’s what those switches actually mean:

* -c: Create an archive.
* -z: Compress the archive with gzip.
* -v: Display progress in the terminal while creating the archive, also known as “verbose” mode. The v is always optional in these commands, but it’s helpful.
* -f: Allows you to specify the filename of the archive.

### Extract an Archive

```bash
tar -xzvf archive.tar.gz
```

It’s the same as the archive creation command we used above, except the -x switch replaces the -c switch. This specifies you want to extract an archive instead of create one.

## Linux: Find out the gost process running background(e.g. node)

```bash
ps -xa | grep node
```
