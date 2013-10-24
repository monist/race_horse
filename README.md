# Race Horse Notes

user-chosen paramaterization of election predictions
  see nytimes app, we want precinct-level

start with washington? virginia?

## factors
* historical voting patterns
* census data
* electoral data (polling info) -- scraped live

[virginia polling CSV files](www.sbe.virginia.gov/sbe_csv/STATS/2013_11_05/)

## client-side

### D3.js
* ++ rendering open source community, tutorials, documentation, etc
* ++ client-side robust 
* ++ pub-sub for data updating
* -- no out-of-the-box graphing capabilities
* -- no ability to hide data
* -- requires modern web-browsers (no IE support)

### client-side JS frameworks
* ember
* backbone
* knockout ***
* angular FUCK NO

## server-side
matters less.... something unobtrusive

* node
* cherrypy
* sinatra
* django, rails -- MVC not so useful
* learn go lang... 

## automated data acquisition

1. acquire and pipe to directory, each channel has its own sub-directory
1. completion of downloading/processing triggers DB import script
1. clean-up raw data directories (delete imported data)

### scraping

* [nokogiri](www.nokogiri.org/)
* [david's kexp scraper](https://github.com/dbalatero/kexp)

### direct download

* bash script? (jaaaaaaaaaaaaaaank) use curl
* python http lib

## user-specified query support

find correlates of past election cycles, client-side?
