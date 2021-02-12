# Reddit Scraper prototype

Records the frequency of keyword mentions in comments on [r/all](https://www.reddit.com/r/all/).  
Data is recorded to a [PostgreSQL](https://www.postgresql.org) database via [Heroku](https://heroku.com).

## Installation

Use [Pip](https://pip.pypa.io/en/stable/) to install.

```bash
pip install
```

## Usage
To start, run the free dyno worker on Heroku.
#### The list of searched keywords can be found in data.json.

## Tools

* [PRAW](https://praw.readthedocs.io/en/latest/) Reddit API.  
* [psycopg](https://www.psycopg.org) PostgreSQL database adapter.  
* [Pip](https://pip.pypa.io/en/stable/) Python package installer.  
* [Heroku](https://heroku.com) Cloud Services.  

## License
[MIT](https://choosealicense.com/licenses/mit/)
