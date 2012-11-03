Munin-Graphite
==============
Munin-node is great. It's simple, elegant, and nicely packaged for nearly every platform. The munin collection tools are ugly, static, and slow. This project aims to allow users to send statistics directly to Graphite without the collector at all.

## Installation
This system is packaged as a rubygem, but it's not available via rubygems.org yet. For now do the following:

1. `git clone https://github.com/skottler/munin-graphite`
2. `cd munin-graphite`
3. `gem build munin-graphite.gemspec`
4. `gem install munin-graphite-0.1.gem`

## License
See LICENSE. This project is licensed under the GNU public license version 3.
