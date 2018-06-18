# ig-scrap-tools

This project makes easy to extract informations from Instagram, without using official APIs by scraping third party services (Online Web Viewers).

## Getting Started

Simply download the project and, if dependencies are installed, run "python _main.py" and follow instructions.

### Prerequisites

This project requires Python 2.7 to be installed.

#### Dependencies:

For a correct execution of this code you need to install the following libraries:
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) - v4.6.0 (or higher)
* [pandas](https://pandas.pydata.org)
* [openpyxl](https://openpyxl.readthedocs.io/en/stable/)

## Usage

* python _main.py   -->   *Interactive*
* python _main.py --user **'username'**   -->   Srcap a profile starting from username
* python _main.py --word **'word'**   -->   Search for hashtags and usernames similar to a certain word
* python _main.py --loc **'locID'**   -->   Search for posts that where posted in a certain location
  *  **'locID'** must be in the form **'locationName'_/'locationNumber'**
* python _main.py --post **'postID'**   -->   Scrap a single post by passing a post number
  *  **'postID'** must be in the form **'postNumber'_'profileNumber'**

## Built With

* [Anaconda](https://anaconda.org/)

## Authors

* **Angelo Pes**

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details
