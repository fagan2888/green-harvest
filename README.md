# Green Harvest

A library that aims to provide a singular interface to state cannabis licensing data. It abstracts the details around fetching and parsing the license documents into a format that can easily be imported into a database for further analysis

The library is currently split into two modules; scrapers.py and parsers.py

## scrapers.py

scrapers.py provides a generic scraping class that handles about 90% of the logic of extracting the download links, fetching the files, and saving them to disk. It also provides classes configured to download data from several states.

## parsers.py

parsers.py intends to provide a similar unified interface for extracting data from the files downloaded. Only Colorado is currently implemented.


## TODO

States that need scrapers

- [ ] Alaska (Documents Found)
- [ ] Arizona
- [x] California
- [x] Colorado
- [ ] Connecticut
- [ ] Delaware
- [ ] Florida
- [ ] Hawaii
- [ ] Illinois
- [ ] Maine
- [ ] Maryland
- [ ] Massachusetts
- [ ] Minnesota
- [ ] Nevada
- [ ] New Hampshire
- [ ] New Jersey
- [ ] New Mexico
- [ ] New York	(Documents Found)
- [x] Oregon
- [ ] Pennsylvania
- [ ] Rhode Island
- [ ] Vermont
- [x] Washington	(Documents Found)
- [ ] Washington, D.C.

States that need parsers

Everything that isn't Colorado

