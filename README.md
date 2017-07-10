# pg_fossa
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Ffossas%2Fpg_fossa.svg?type=shield)](https://app.fossa.io/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Ffossas%2Fpg_fossa?ref=badge_shield)


PostgreSQL extension for Fossa

## Install

1. Add pg_fossa to your extension share directory: `cp ./* $(pg_config --sharedir)/extension/`
2. Execute `CREATE EXTENSION pg_fossa` in your PostgreSQL database

## Upgrade

1. Add pg_fossa to your extension share directory: `cp ./* $(pg_config --sharedir)/extension/`
2. Execute `ALTER EXTENSION pg_fossa UPDATE` in your PostgreSQL database

## Check Version

To see the version of this plugin installed, execute `SELECT fossa_version()` in PostgreSQL.

Another option is to try interrogating the description via `\dfnS+ fossa_dependencies`.


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Ffossas%2Fpg_fossa.svg?type=large)](https://app.fossa.io/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Ffossas%2Fpg_fossa?ref=badge_large)