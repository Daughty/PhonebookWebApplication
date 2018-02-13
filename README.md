# PhonebookWebApplication
Phonebook with google contacts type of UI.

The database query :-

CREATE TABLE address (id INT(4) NOT NULL AUTO_INCREMENT PRIMARY KEY, name VARCHAR(30), phone VARCHAR(30), email VARCHAR(30));
INSERT INTO address (name, phone, email) VALUES ( "Alexa", "430-555-2252", "sunshine@fakeaddress.com"), ( "Devie", "658-555-5985", "potato@monkey.us" ),
("Daughty","9805049643","daughty178@gmail.com,")

The above table address is created inside test database.

Both address.php and form.php have connection setup to database.
Both files need change of username and password accordingly.

The functionalities provided are:-
1.Add contact.
2.Edit contact.
3.Remove contact.
4.Summary.
5.Search a contact.


