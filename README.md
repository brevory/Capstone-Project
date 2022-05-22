Knowledge Scrape is a technology built to make students lives easier.
Knowledge Scrape is designed to pull in information
on acadmeic research and researchers through various apis and
the results of a user's search can be
filtered in a variety of ways to attain the most relevant information
to them.
Users can login or sign up establishing a session and connecting
to an sqlite3 db and they can bookmark articles
for future reference
Knowledge Scrape also has some webscraping action to identify the subject of 
an article via the Beautiful Soup parser

To begin all you need to do is download or clone this repository navigate 
to the applications directory in your powershell if needed and enter the following 
commands
$env:FLASK_APP = "app"
flask run
