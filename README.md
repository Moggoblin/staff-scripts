# staff-scripts

Collection of useful scripts to automate RD2L staff tasks.

### draft_sheet_parser.py
generates the liquipedia list of teams by parsing the google spreadsheet automatically (the team draft sheet)

### liquipedia_map.py
generates liquipedia Map text from a match ID (picks, bans, time, winner)

### liquipedia_playday.py
generates liquipedia Match2 text for a complete playday

requires:
1) Parsed spreadsheet output (done with draft_sheet_parser)
2) Steam API token (obtainable under https://steamcommunity.com/dev/apikey) in key.txt 
3) filling in some inputs for search at the top of the script
