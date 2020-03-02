# SentinelDownlader
The file dhusget.sh of the [Copernicus Open Access Hub](https://scihub.copernicus.eu/) is provided by ESA to allow multiple downloads of the Sentinel products.
The use of [dhusget_plus.sh](./dhusget_plus.sh ) is the same of the use of dhusget.sh described [here](https://scihub.copernicus.eu/userguide/BatchScripting#dhusget_script).
The "-Q" command has been added to the file [dhusget_plus.sh](./dhusget_plus.sh ) to filter the relative orbit number.

## Usage
SEARCH QUERY OPTIONS

-Q (relative orbit n)		: relative orbit. Possible options are: (1,2,...,175);

## Example
dhusget_plus.sh [LOGIN OPTIONS]... [SEARCH QUERY OPTIONS (... -Q 175 ...)]... [SEARCH RESULT OPTIONS]... [DOWNLOAD OPTIONS]...

