### GSD is a simple way to block distracting sites when you want to concentrate.

### Usage

  - `sudo gsd work`   - block all sites in sites.ini
  - `sudo gsd play`   - unblock all sites in sites.ini
  - `sudo gsd status` - detect if sites are currently blocked or unblocked

### Installation

Make sure that you edit `distaction_sites` to add the sites that you want to block.

``` bash
$ git clone https://github.com/taylorlapeyre/gsd.git
$ cd gsd
$ rake
```