# Datamuse_apiWord-
The Datamuse API is a word-finding query engine for developers. 
You can use it in your apps to find words that match a given set of constraints and that are likely in a given context. 
You can specify a wide variety of constraints on meaning, spelling, sound, and vocabulary in your queries, in any combination.  
The API gives you programmatic access to most of the functionality of Datamuse's websites, including OneLook, 
RhymeZone, Rimar.io, and WikSearch.

A query string contains additional information to be sent with a request. 
The Datamuse API allows us to retrieve more specific data with query strings attached to the request URL.

Wiki: query string
A query string is separated from the URL using a ? character. 
After ?, you can then create a parameter which is a key value pair joined by a =. Examine the example below:

'https://api.datamuse.com/words?key=value'
If you want to add an additional parameter you will have to use the & character to separate your parameters. Like so:

'https://api.datamuse.com/words?key=value&anotherKey=anotherValue'
