# RBGE-vanderbot-wikidata

This script is a slightly edited version of the VanderBot script found here [vanderbi.lt/vanderbot](https://github.com/HeardLibrary/linked-data/blob/master/vanderbot/README.md), along with other accompanying code. 

To use the script I'd recommend following the procedures outlined in that article. Useful tutorials can also be found [here](http://baskauf.blogspot.com/2021/03/writing-your-own-data-to-wikidata-using.html), for uploading data to Wikidata using this script. 

The script works in exactly the same way as VanderBot in creating or updating files to Wikidata. The alterations made change how aliases uploads function. 
With this script, aliases can be uploaded onto Wikidata under a labeled heading of 'aliases' in the csv file. 

Beneath this heading, aliases for an item follow in the following format:

["aliases1", "aliases2", "aliases3"] 

## Limitations

Through the script aliases will only update if there are more aliases being inputted than already exist in a wikidata profile, otherwise the present alias list will not update. As a result,
this tool is more useful in Wikidata entry creation rather than editing at this moment. 

The other limitation is that aliases can only be inputted in one language currently. 

## Use

This piece of code has been used to upload and update entries relating to RBGE collections, including Expeditions and authority/agent files from Herbarium, living collections and library 
collection management systems. 

