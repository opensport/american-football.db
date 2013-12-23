# Welcome to `american-football.db`

A free open public domain National Football League (NFL) database 'n' schema
for use in any (programming) language
(e.g. uses plain text fixtures/data sets).


## Usage

Use the `sportdb` command line tool to build your own `football.db` copy
from the plain text fixtures.  Example:

Step 1:  Get a copy of the `world.db` fixtures

    $ git clone git://github.com/openmundi/world.db.git

Step 2:  Get a copy of the `american-football.db` fixtures

    $ git clone git://github.com/opensport/american-football.db.git

Step 3:  Let's build the `football.db`

    $ sportdb setup --include ./american-football.db --worldinclude ./world.db

That's it.
See the [`sportdb` command line tool project](https://github.com/geraldb/sport.db.ruby) for more.


## License

The schema, data and scripts are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to the [Open Sports Database & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!
