# IPTV Blacklist

## Overview
This repository hosts blacklist files for various countries and categories, specifically designed to enhance the user experience by removing IPTV streams that are problematic. These issues include CORS (Cross-Origin Resource Sharing) problems, unreachable streams (e.g., HTTP 404 errors), and other access or reliability issues. The guiding principle is simple: if a stream does not work, it is removed to prevent a poor user experience.

## Structure
The blacklist files are organized into two main folders within the `blacklists` directory:

- `blacklists/countries/`: Contains blacklist files named according to the ISO country code of the country they pertain to, with a postfix '_blacklist.json'. For example:
  - `blacklists/countries/us_blacklist.json` for the United States
  - `blacklists/countries/de_blacklist.json` for Germany
  - `blacklists/countries/jp_blacklist.json` for Japan

- `blacklists/categories/`: Contains blacklist files for various categories. These files help in filtering streams by specific types or genres of content. For example:
  - `blacklists/categories/news_blacklist.json` for category `news`
  - `blacklists/categories/sports_blacklist.json` for category `sports`
  - `blacklists/categories/music_blacklist.json` for category `music`

## Usage
These blacklist files are designed to filter out non-playable IPTV sources in applications and services that stream television content over the internet.

## License
This project is dedicated to the public domain under the Unlicense, which releases all copyrights and related rights, allowing anyone to copy, modify, distribute, and use the work for free, without any restrictions whatsoever. See the [LICENSE](LICENSE) file for more details.

## Disclaimer
These lists are provided for informational purposes only and do not constitute legal advice. Users are responsible for ensuring their compliance with all applicable laws and regulations.
