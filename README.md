# Welcome to `american-football.db`

A free open public domain National Football League (NFL) database 'n' schema
for use in any (programming) language
(e.g. uses plain text fixtures/data sets).


## Usage

Use the `sportdb` command line tool to build your own `football.db` copy
from the plain text fixtures.  Example:

Step 1:  Get a copy of the `world.db` fixtures

    $ git clone git://github.com/geraldb/world.db.git

Step 2:  Get a copy the `nfl.db` fixtures

    $ git clone git://github.com/geraldb/american-football.db.git

Step 3:  Let's build the `football.db`

    $ sportdb setup --include ./american-football.db --worldinclude ./world.db

That's it.
See the [`sportdb` command line tool project](https://github.com/geraldb/sport.db.ruby) for more.



## Links

- Official site -> [`nfl.com`](http://nfl.com)

<!-------- some facts ------------>

- 32 teams
  - 16 teams in the National Football Conference (NFC) and
  - 16 teams in the American Football Conference (AFC)
- 17-week regular season
  - week after Labor Day to week after Christmas
- Playoffs
  - 2 x 6 teams (4 division winners + 2 wild-card teams) from each conference 
- Super Bowl / Final
  - champion NFC vs champion AFC

### Wikipedia

- [National_Football_League](http://en.wikipedia.org/wiki/National_Football_League)
- [2013_NFL_season](http://en.wikipedia.org/wiki/2013_NFL_season)


## License

The schema, data and scripts are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to the [Open Sports Database & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!
