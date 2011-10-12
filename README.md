*trychooser* is a program which asks you questions and creates a TryChooser syntax for you. It is structured as a hg extension, but it should also work as a command-line program.

### Installation

To install, add this line to you .hgrc:

    [extensions]
    trychooser = path/to/trychooser


### Running

To push to tryserver after asking you questions, type:

    $ hg trychooser


### Command line

To just read get a trysyntax from the command line:

    $ ./trychooser


### Testing

To run the tests, run

    $ ./trychooser_test


### Meta

Based on Lukas Blakk's web version [UI](http://people.mozilla.org/~lsblakk/trychooser/trychooser.html)-[Code](http://hg.mozilla.org/build/tools/trychooser)
See also the [TryChooser page](https://wiki.mozilla.org/ReleaseEngineering/TryChooser)

Bugs and patches via [Github](https://github.com/pbiggar/trychooser)
