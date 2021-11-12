# lgtm

lgtm is a simple tool for helping LGTM fancy text message to clipboard via command line. LGTM is an abbreviation for
**Looks Good To Me**. Generally, it is used during code reviews when the pull request is ready to merge on main branch. Its
usage is so simple.

## Setup

You can use `setup` script to make script ready for your environment.

```shell
$ chmod +x setup
$ ./setup
```

It creates a symbolic link like a shortcut in Windows. Be aware of the location of the creating symbolic link. On my
machine, I prefer to locate on `/usr/local/bin`. If it does not work for your machine, you can change with
another `$PATH` directory.

## Run

Now, it is ready to run this command from anywhere. To make sure that it is working on other directories, you can change
your directory and run the following command.

```shell
$ lgtm
```

Finally, you can use this command anytime that you need. It basically copies the LGTM fancy test to your clipboard. 

## LICENSE

[MIT](https://github.com/gozeloglu/lgtm/blob/main/LICENSE)