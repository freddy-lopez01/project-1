CS 322 - Project-1.
* Author: Freddy Lopez
* Student ID: flopez2 

* the purpose of this project was to corrrectly implement a file checking structure for the exisiting server. I obtained the DOC_ROOT from credentials.ini via the options.DOCROOT in main() in order to change the CWD to route to the /pages folder. Then in the respond() function, I implemented three different types of checks in order to vet the file that the user requested access to. If the file exists in the DOCROOT specified directory, the code exceutes and trasmits the data contained by the file to the webpage. If a file does not exist in the CWD, the error code 404 NOT FOUND is displayed on the webpage along with my custom image. If the file begins with illegal characters ~ or .. then error code 403 FORBIDDEN is displayed along with a custom statement I put to display alongside the error code. 
