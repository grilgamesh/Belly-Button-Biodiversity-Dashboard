# IWV
week 14 homework: Interactive Web Visualisations


This project reads an external Json file, and creates two functions: an update, an an init, then calls the init function.

the update function takes an id number, then searches the json for the id. it gets the location of the id, then uses that location number to copy the need data into arrays, and draws three charts of the data - see the code comments for details of how.

the init function uses the update function to instantiate the page in the first place, by passing the id value of the first data in the array.
