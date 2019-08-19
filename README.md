# EP2-Data
Eclipse Phase Second Edition Data

This work is licensed under the Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license: https://creativecommons.org/licenses/by-nc-sa/4.0/ as this is the license of the EP2E book.

This repo is following these guidelines:
* Lowercase keys on objects
* Avoid abbreviations in keys (e.g. 'description' not 'desc')
* Include an 'id' attribute (UUIDv4) on objects you're adding to the data for the first time
* Underscores in keys, not spaces or pascal/camel-case
* Include information about the source in 'resource' and 'reference' attributes
  * 'resource' is something like the name of the book
  * 'reference' is a locator inside that resource like a page number
* 2-space tab (not that it matters much)
* Paragraphical data stored in an array of paragraphs
* Lists (sorted and unsorted) stored in an array, sub-lists in a nested array
* Every samey object has all the keys, even if only one object needs it (though you should reconsider your structure at that point)
