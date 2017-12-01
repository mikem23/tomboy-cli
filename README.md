# tomboy-cli: a simple cli interface for Tomboy

This is a simple command line tool for interacting with Tomboy.

This is *preliminary work* and only supports a few basic commands.

I have written it to do the things I need it to. It is currently
not really configurable. It can do simple things like:

* list notes
* display a note
* duplicate a note
* open the start note
* tag a note
* watch tomboy activity

Essentially, this is the functionality that Tomboy provides via its
[dbus interface](https://arstechnica.com/information-technology/2007/09/using-the-tomboy-d-bus-interface/)

```
Usage: tb [OPTIONS] COMMAND [ARGS]...

Options:
  --help  Show this message and exit.

Commands:
  dup     Duplicate a note
  list    List notes
  mknote  Create a note from stdin or file
  show    Output the contents of the note
  start   Display the Start Here note
  tag     Add a tag to a note
  watch   Watch Tomboy activity
```

This is toy software and should not be considered stable.
