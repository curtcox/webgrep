# webgrep

An extremely minimal implementation of incremental searching.
It is written in groovy and uses the web server built into any recent Java
to grep the specified directory. It is intended to provide a staring point to a
more useful and extensive search.

## Warning

Running this app exposes the contents of your filesystem to any computer
that can access it.

## Usage

Specify the directory that you want to search on the command line.

```
./search /path/of/dir/to/search
```

## Installation

This requires [GroovyServ](https://kobo.github.io/groovyserv/index.html)
which requires Groovy which requires Java.
Those are all generally available from package managers.
The scripts are launched via [Shebangs](https://en.wikipedia.org/wiki/Shebang_(Unix)),
so an environment that supports them is required.
