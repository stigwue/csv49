# CSV49

CSV49 is Comma Separated Values For Nigeria: a set of commonly used Nigerian data. This forgives you for wasting productive human hours reinventing the wheel provided you prevent the next developer from doing the same.

## API

For some, the data as CSV might not be enough. I'm taking steps to have it available also as an API. Relax, it is nothing too serious: just JSON files over which you can do some primitive querying. The first step is changing some of the CSV formats and that is what you see in the json folder.

The final product should live at [api.csv49.xyz](https://api.csv49.xyz) and should be available at no cost except one of you decides to hook it up to something that queries it beyond reasonable limits, say every 9ms. You'll then be invited to host your JSON files yourself.

## Contribute

### Modifications needed

This project is old (since 2013 in fact) and a lot of these data sets were from assumptions that are no longer true. Find one and fix it and you will have our utmost respect.

For instance, CSV4: GSM provider prefixes, existed before number protability happened so if you have some other way to determine which network a number belongs to, share! Things like states and local government areas (LGA) tend to change only during military regimes so we should be good ;-)

A lot of things need specificity, such as:

* Geolocation data needing specifics e.g CSV3: States. LGAs and Geolocation

* Classification to be more useful e.g CSV7: Universities, Polytechnics and Colleges

### Requests for CSVs

There are other datasets out there that you may have and can contribute. Please make sure to abide by all laws. We would not want you putting private or protected data on here. A few that come to mind include:

* Nigerian vehicle number plate schema especially for LGAs and state agencies

* Airports codes and classification (local or international)

### How do I contribute

Like all things open source: fork this repository, do the awesome contribution you have, submit a pull request and that should be it!

## List

* [CSV49](./csv/csv49.csv): Comma Separated Values For Nigeria: a set of commonly used Nigerian data by [@stigwue](http://twitter.com/stigwue)

* [CSV1](./csv/csv1.csv): States codes and geopolitical zones by [@stigwue](http://twitter.com/stigwue)

* [CSV2](./csv/csv2.csv): Geopolitical zones by [@stigwue](http://twitter.com/stigwue)

* [CSV3](./csv/csv3.csv): States. LGAs and Geolocation by [@kehers](http://twitter.com/kehers)

* [CSV4](./csv/csv4.csv): GSM Network Providers Phone Number Prefixes by [@stigwue](http://twitter.com/stigwue) and [@pystar](http://twitter.com/pystar)

* [CSV5](./csv/csv5.csv): States and Capital Geolocation by [@stigwue](http://twitter.com/stigwue)

* [CSV6](./csv/csv6.csv): Universities by [@kehers](http://twitter.com/kehers)

* [CSV7](./csv/csv7.csv): Universities, Polytechnics and Colleges by [@funsholaniyi](http://twitter.com/funsholaniyi)
