# FBLA-Tourism-Search

***

### 2021-2022 FBLA Project
Created by Michelle McAveety at Freedom High School for the FBLA Coding and Programming competition

***

### Purpose
A program created to assist in searching popular tourist attractions in the state of Florida

### Features

+ Lists all available tourist attractions
+ Filter the list search by attraction name, type, group size, rating, and price!
+ 185 entries to search through!

***
### Disclaimers

+ All location name, address, telephone, and description data was accessed from https://www.florida-backroads-travel.com/florida-tourist-attractions.html
+ Entries were omitted in scenarios where the aforementioned data was missing or inconsistent
+ Data was unaltered except to improve clarity or program functionality.
+ Location type, group size, rating, and price data were generated for purposes of program search functionality. 
+ Location type was assigned algorithmically where "museum" or "park" was present in location name. Remaining entries were manually assigned location types.
+ Location group size was algorithmically assigned based on location type. In instances where location type was "other", group size was manually assigned.
+ Location rating was pseudorandomly assigned to each entry.
+ Location price was algorithmically assigned based on location description and manually checked for accuracy.

***

## Checklist

***

Fixing Data

-[x] Create disclaimer about data

-[x] Parse locations.json

-[x] Add all keys to .json data

-[x] Fix location descriptions
 
 ***
 
Filtering Data

-[ ] Create .json filter for searching

-[ ] Create search method using HTML form inputs

 ***
 
HTML Page Formatting

-[ ] Finalize HTML form so the inputs are relevant to the .json data

-[ ] Format HTML page

-[ ] Reset button? Live search (no submit button needed)?
