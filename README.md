# Contact List
Playground Contact Book that tells who's birthday is next in your contact list

## Technical Description
* Leverage system APIs to access the address book on Apple ID
* Import Cocoa module instead of UIKit. Cocoa contains a core set of system modules
* Import another framework, Contacts, for accessing contacts on the user's device. 
* Contact is stored in a model, phone type is enum
* Add the date of birth. 
* In the system contacts it is stored as a component
* To generate the contacts, we will create a small function that creates a contact with the date of birth passed in, and fills the other fields with standard data by adding a suffix. 
* Store contacts in an array, but it's better to create a specialized container that provides helper methods. Container would be better to be a collection. 
* To get a default implementation for search, iteration, and other collection features a newly created protocol inherits from RandomAccessCollection.
* UpcomingBirthday is  an alias for the tuple containing the date and an array of birthday people for that day. 
* Add to it the sorting function by first or last name. 

