# Lists and Data for Designers
Set of sample lists and data for populating interface design in Figma or Sketch.

This repository is a gallery of real content ready to populate your mockups, built by designers who want to work more efficiently. 

The sample data collections are organized in two formats, depending on how you want to populate your mockups:

- TXT files (simple) - for entering a single entity with a line break separating each entity. `(e.g.: names)`
- JSON files (advanced) - for boosting your productivity and entering the entire data set at once. `(e.g.: Names, Title, Company, Address)` 

## TXT file example

Example: `teamsnba.txt`
```html
Atlanta Hawks
Boston Celtics
Brooklyn Nets
Charlotte Hornets
Chicago Bulls
...
```

## JSON file example

Example: `teamsnba.json`
```json
[
  {
    "teamId": 1610612737,
    "abbreviation": "ATL",
    "teamName": "Atlanta Hawks",
    "simpleName": "Hawks",
    "location": "Atlanta"
  },
  {
    "teamId": 1610612738,
    "abbreviation": "BOS",
    "teamName": "Boston Celtics",
    "simpleName": "Celtics",
    "location": "Boston"
  },
  {
    "teamId": 1610612751,
    "abbreviation": "BKN",
    "teamName": "Brooklyn Nets",
    "simpleName": "Nets",
    "location": "Brooklyn"
  },
  {
    "teamId": 1610612766,
    "abbreviation": "CHA",
    "teamName": "Charlotte Hornets",
    "simpleName": "Hornets",
    "location": "Charlotte"
  },
  {
    "teamId": 1610612741,
    "abbreviation": "CHI",
    "teamName": "Chicago Bulls",
    "simpleName": "Bulls",
    "location": "Chicago"
  }
]
```


## Suggest a list
- Add an [issue](https://github.com/mpaiva/lists-and-data-for-designers/issues "issue") and provide a few sample entities.


## Contribute
With your help, Lists will ultimately gather all the data types designers could ever need.  Join us on our adventurous journey.

### Edit a list
- Download or fork the repository.
- Edit the list. 
- Push to your fork and submit a pull request. Make sure to explain what's new.

### Create a list
- Download or fork the repository.
- Add your new list by creating another .txt or .json file.
- Push to your fork and submit a pull request. Make sure to explain what's new.

### Naming convention
Any list can be language specific, or country specific. Our naming convention uses language and/or country codes to deal with these intricacies. Below are a few examples explaining how we name lists.

```html
985
756
507
964
309
...
```
`numbers100to999.txt` is language and country agnostic, no language/country code.

```html
Paleo Pumpkin Bread
Double Broccoli Quinoa
Deep Dish Fruit Pizza
Baked Chicken and Spinach Flautas
Homemade Strawberry Lemonade
...
```
`recipes-en.txt` is a list in english, so we use the `-en` suffix.

```html
972 Sylvan Street South Angelina, NL S0B2V9
11907 Doyle Cape Cydneyview, MB H5B 2V2
8832 Adah Vista South Guido, PE B2P-1J8
52906 Danyka Freeway Port Michaelborough, NU N7L8L2
89913 Gottlieb Forks Suite 588 Schadenport, YT A0A-0H9
...
```
`address-en_CA.txt` is a list in english, and it's specific to Canada, so we use the `-en_CA` suffix.

## Credits
Shamelessly inspired on [List for Designers](https://github.com/listsfordesign/Lists "List for Designers"), which only handles single entity TXT files.
