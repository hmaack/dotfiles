# My dotfiles

Manage configuration files for:

* sublime text 3

and set OS X system defaults. Thank you @heisam.

## Requirements

Tested on OS X Yosemite (10.10.2) with rvm based Ruby (2.2.*). See detailed [manual setup instructions](manual_setup.md).

## Installation

1. Install [Peridot](https://github.com/svenwin/peridot) via:

    ```bash
    $ gem install peridot
    ```

2. clone repository via:

    ```bash
    $ git clone https://github.com/rocknruby/dotfiles.git
    ```

## Usage

**IMPORTANT** These tasks will replace your existing config files without warning!

```bash
$ rake -T

$ rake dotfiles:sublime    # Link Sublime configuration files
$ rake watch               # Watches for changes and reruns rake
```

## License

These dotfiles are released under the [MIT License](http://opensource.org/licenses/MIT).