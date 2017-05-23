There are a few ways of installing Octave.

### Note -- there is an in-browser option

If you don't want to fuss with installing a pretty large binary (around 1gb on mac),
use [Octave-Online.net](https://octave-online.net/). Signing in will allow things
like sync to google docs and "collaboration" mode.

# Installing on Mac

If you're on MacOS:

#### [Download .dmg from sourceforge](https://sourceforge.net/projects/octave)

or

#### [Install via Homebrew](http://sourabhbajaj.com/mac-setup/Apps/Octave.html)

The latter may require a few extra configuration steps...

#### [Read this post if you encounter issues](https://adampash.com/how-to-install-octave)

There is additional info in the [official guide](http://wiki.octave.org/Octave_for_MacOS_X),
but personally I found this page a big confusing.

# Installing on Windows

Install the latest binary from [here](https://ftp.gnu.org/gnu/octave/windows/).
That would be `octave-4.2.1-w64-installer.exe` or `octave-4.2.1-w32-installer.exe`
depending on the architecture of your cpu.

# Installing for GNU/Linux

Generally you may use the preferred package manager for your distribution.
These include:
- [Debian](http://wiki.octave.org/Octave_for_Debian_systems)
- [Ubuntu](https://unix.stackexchange.com/questions/280195/how-to-install-octave-without-gui-in-ubuntu-16-04)
- Fedora
- Gentoo
- openSUSE

If you're using one of these, you're probably familiar with googling the appropriate steps
for your distribution and version. Most of them involve `wget` pointed at a gzip file
such as

```shell
$ wget -c ftp://ftp.gnu.org/gnu/octave/octave-4.0.0.tar.gz
$ tar xzvf octave-4.0.0.tar.gz
```


## Further resources

- [Official Docs (html)](https://www.gnu.org/software/octave/doc/interpreter/index.html)
- [Official Docs (pdf)](https://www.gnu.org/software/octave/octave.pdf)
- [Packages for Octave (:star:)](https://octave.sourceforge.io/packages.php)