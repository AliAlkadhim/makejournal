This script allows you to make a journal layout. 

# Usage
You have to provide `--start_month,  --start_day, end_month, --end_day` as arguments. This creates a Microsoft Word document with a journal entry for each day in this range. For example

`python makejournal.py --start_month 5 --start_day 12 --end_month 7 --end_day 15`

Makes a journal entry for everyday in that range in a word document of the name format `JOURNAL_STARTING_FROM_<Start_Date>_TO_<End_Date>`

TODO: Make Graphical User Interface
