# Redmine Projects-Queries Extension plugin

This plugin adds new filters and columns to projects queries.

It is only compatible with Redmine 4.1.0 and above.

This plugin is a fork from the [Better CrossProjects](https://github.com/jbbarth/redmine_better_crossprojects) plugin and you should continue to use this one if you are running Redmine 4.0.x or Redmine 3.


## Installation

Please apply general instructions for plugins [here](http://www.redmine.org/wiki/redmine/Plugins).

Requirements:

    ruby >= 2.3.0
    
Note that this plugin now depends on:
* **redmine_base_deface** which can be found [here](https://github.com/jbbarth/redmine_base_deface)

First download the source or clone the plugin and put it in the "plugins/" directory of your redmine instance. Note that this is crucial that the directory is named 'redmine_projects_queries_extension' !

Then execute:

    $ bundle install
    $ rake redmine:plugins

And finally restart your Redmine instance.

This plugin is only compatible with Redmine 4.1.0 and above.
Please feel free to report any bug you encounter.

## Test status

|Plugin branch| Redmine Version   | Test Status       |
|-------------|-------------------|-------------------|
|master       | master            | [![Build1][1]][5] |
|master       | 4.1.1             | [![Build1][2]][5] |

[1]: https://travis-matrix-badges.herokuapp.com/repos/nanego/redmine_projects_queries_extension/branches/master/1?use_travis_com=true
[2]: https://travis-matrix-badges.herokuapp.com/repos/nanego/redmine_projects_queries_extension/branches/master/2?use_travis_com=true
[5]: https://travis-ci.com/nanego/redmine_projects_queries_extension

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
