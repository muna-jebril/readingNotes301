Intro to EJS - Overview - 1

is a simple templating language that lets you generate HTML markup with plain JavaScript.
Advantages
Fast development time
Simple syntax
Speedy execution


Working with volumes
You can perform a volumes search by sending an HTTP GET request to the following URI:

https://www.googleapis.com/books/v1/volumes?q=search+terms

This request has a single required parameter:

q - Search for volumes that contain this text string. There are special keywords you can specify in the search terms to search in particular fields, such as:
intitle: Returns results where the text following this keyword is found in the title.
inauthor: Returns results where the text following this keyword is found in the author.
inpublisher: Returns results where the text following this keyword is found in the publisher.
subject: Returns results where the text following this keyword is listed in the category list of the volume.
isbn: Returns results where the text following this keyword is the ISBN number.
lccn: Returns results where the text following this keyword is the Library of Congress Control Number.
oclc: Returns results where the text following this keyword is the Online Computer Library Center number


Download Format
You use the download parameter to restrict the returned results to volumes that have an available download format of epub by setting the to the value epub.


Projection
You can use the projection parameter with one of the following values to specify a predefined set of Volume fields to return:

full - Returns all Volume fields.
lite - Returns only certain fields. See field descriptions marked with double asterisks in the Volume reference to find out which fields are included.