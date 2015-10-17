# checkstyle
Script to check java coding style

### Usage
1. `git clone git@github.com:vengatlnx/checkstyle.git`
2. `cd checkstyle`
3. `chmod 0755 ./checkstyle`

Add to your `.bashrc` or `zshrc`:

`$ echo 'export PATH=$HOME/checkstyle:$PATH' >> ~/.bashrc`

to run:

```
$ checkstyle [java-file]
$ checkstyle [source-dir]
$ checkstyle sun-check.xml [java-file]
```
By default it runs google check style, you can also specify
sun java or your own custom check-style.xml
