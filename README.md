# gro

**gro** - management utility for a group of local git repositories located in the current directory

## Getting Started

### Prerequisites
gro can be used in any POSIX-compatible operating system, in which there are such standard tools or commands as: sh 


### Installing

#### Manual install
Just copy the executable **gro** file to the directory specified in the \$PATH environment variable

#### Self-installs to $HOME/bin directory:
```
./gro -i
```

#### Self-installs to /usr/local/bin directory:
```
sudo ./gro -i -g
```

Creates symbolic links to the **gro** executable for quick use of basic commands:
```
./gro -ia
```

## Running the tests

The following tools are used for testing:
[shunit2](https://github.com/kward/shunit2)
[shellcheck](https://github.com/koalaman/shellcheck)

Please see the instructions on the web pages of these projects.

```
./gro_test.sh
```

## Versioning

We use [SemVer](http://semver.org/) for versioning.

## Authors

* **Evgeny V. Bogodukhov** - *Initial work* - [evbg](https://github.com/evbg)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
