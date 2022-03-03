# kyruus
Pet Adoption Program

Program imports a CSV file of pets to a hash table. The user can then search for a pet by the ID, Gender, Type, Name, and Location. 

Assumptions are: users will want to add, remove pets from the list as they are adopted, so these functions were added to the Hash class. Also, first paragraph of instruction states ability to search for a pet based off of location, type, and gender, so these functions were added first. Then 'initial' labeled instruction states ability to import pets in bulk, search for a pet by location, type, then by any set of attributes. To make the program more robust, I added the ability to import in bulk using a CSV file, and the ability to search by the pet ID and name. Since customers will often have a wish list of items they would prefer to have in a program, being able to add the additional functionality for the users as an upgrade or enhancement is very beneficial.

The program is extensible/scalable in that the ease in upgrading the program to increase the pet attributes, add additional classes for adoption customers and adoption objects can be accomplished without having to modify the entire program.

I ran out of time to complete a single search function that allows user to search for any combination of pet attributes.

Unit Testing would entail either having a separate QA team do unit testing or engineer doing the unit testing. Test cases would be written up for each user requirement scenario to try and force the function to fail (invalid or unexpected values utilized). Testing of code would be done by creating functions in 'SearchPet' or a separate class that implements the searching functions in 'SearchPet', checks that the functions in 'Hash' allow user to insert and remove pets from the table, and checks that the CSV file imports to the hash table without issue (white box testing, or as much white box testing as allowed for the project; either limited by time or by completing fix of a percentage of errors). 
