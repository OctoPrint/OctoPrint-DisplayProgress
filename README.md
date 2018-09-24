**⚠ Up for adoption! ⚠**

I have my hands way too full with OctoPrint's maintenance to give this plugin the attention it needs. Hence I'm looking for a new maintainer to adopt it. [Please get in touch here](https://github.com/OctoPrint/OctoPrint-DisplayProgress/issues/10).

---

# OctoPrint-DisplayProgress

Displays the print progress on the printer's display.

![Example](http://i.imgur.com/F4m2QlB.jpg)

## Setup

Install via the bundled [Plugin Manager](https://github.com/foosel/OctoPrint/wiki/Plugin:-Plugin-Manager)
or manually using this URL:

    https://github.com/OctoPrint/OctoPrint-DisplayProgress/archive/master.zip

## Configuration

``` yaml
plugins:
  displayprogress:
    # The message to display. Placeholders:
    # - bar: a progress bar, e.g. [######    ]
    # - progress: the current progress as an integer between 1 and 100
    message: '{bar} {progress:>3}%%'
```
