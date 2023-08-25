# RBGE-vanderbot-wikidata

This script is a slightly edited version of the VanderBot script found here vanderbi.lt/vanderbot. 
To use the script I'd recommend following the procedures outlined in that article.

The script works in exactly the same way as VanderBot in creating or updating files to Wikidata. The alterations made have just changed how aliases function. 
With this script aliases can be uploaded onto Wikidata through specific formating under a labeled heading of 'aliases'. Beneath this, aliases for an item follow in the following format:

["aliases1", "aliases2", "aliases3"] etc etc... 

Through the script aliases will only update if there are more aliases being inputted than already exist in a wikidata profile, otherwise the present alias list will not update. As a result,
this tool is more useful in Wikidata entry creation rather than editing at this moment. 

The other limitation is that aliases can only be inputted in one language currently. 

This piece of code has been used to upload and update entries relating to RBGE collections, including Expeditions and authority/agent files from Herbarium, living collections and library 
collection management systems. 

