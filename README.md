<h2><p align=center> Mission-To-Mars </p> </h2>

<h3><p> Purpose </p></h3>

Write a script to automate the task of searching for required information, store it all in one convenient location and once gathered, display it in the form of a webpage. 

<h3><p> Resources: </p></h3>

Data Source: internet

Software: HTML, CSS, Splinter, BeautifulSoup, MongoDB, Bootstrap, Flask

<h2><p> Project Overview </p></h2>

Web scraping was done from the web-scraping friendly websites to obtain the latest article providing information about NASA's Mars Mission.

- The scraping script was written in Python with the help of BeautifulSoup to convert the data in browser instance in the form of soup object(similar to JSON object). 
- Splinter was used to automate the process of getting (scraping) latest information on a click of a button, everytime we need it. 
- The scraped data, being unstructured, was stored in MongoDB.
- Flask was used to create a webpage by performing following functions:

      1. Use scraping module & python script to scrape new data.
      2. Store the scraped data into MongoDB.
      3. Get the scraped data from MongoDB and then display it on the webpage 
         with render_template & index.html
    
- The css, bootstrap were used to prettify the webpage.

<h2> Results </h2>

<p>

</P>

<kbd>
  
![Screen Shot 2022-01-09 at 9 54 08 PM](https://user-images.githubusercontent.com/90424752/148723566-4b15f0b9-5784-431f-840f-4e2a1a8fd305.png)

</kbd>


