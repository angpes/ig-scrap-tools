# ig-scrap-tools

This project makes easy to scrap informations from Instagram, without using official APIs by scraping third party services (Online Web Viewers).

## Getting Started

Simply download the project and, if dependencies are installed, run "python _main.py" and follow instructions.

### Prerequisites

This project requires Python 2.7 to be installed (it can run on Python 3 by making a few mods)

#### Dependencies:
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
* [pandas](https://pandas.pydata.org)
* [openpyxl](https://openpyxl.readthedocs.io/en/stable/)

## Usage

* python _main.py   -->   Interactive
* python _main.py --user %username%   -->   Srcap a profile starting from username
* python _main.py --loc %locationID%   -->   Scrap for posts using a certain location
* python _main.py --post %postID%   -->   Scrap a single post by passing a post number
* python _main.py --word %word%   -->   Look for hashtags and usernames similar to a certain word

## Built With

* [Anaconda](https://anaconda.org/)

## Authors

* **Angelo Pes**

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details
