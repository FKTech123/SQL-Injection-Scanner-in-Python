# SQL-Injection-Scanner-in-Python

## Approach
* Import module
* Now, initialize the session of HTTP and set the latest user agent for your browser
* Now we shall extract the HTML web forms.
  * For this, first, we will write a function that upon giving a URL, will make a request to that page and will extract all the HTML form tags from it
  * Then return these tags as a list.
  * We can then use this list afterward.
* Now we will check that whether the obtained page has any SQL vulnerabilities or not from its response output.
* If it has any syntax error, the page is vulnerable. Although there are a lot of database errors we will search with limited database errors that is Oracle and SQL Server Errors, because these two are mostly used.
* Now we will apply this search approach for all the forms in the HTML web page for the error
* Our script is ready, and we will now test it.
  * We will pass the URL upon which we have to detect SQL injection.
  * So we will pass the URL argument through the command line.
