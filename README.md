**⚠ Looking for maintenance help/adoption! ⚠**

I have my hands way too full with regular OctoPrint maintenance, so any help with maintaining this plugin or even outright adoption would be greatly appreciated!

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
