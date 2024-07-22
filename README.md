# data_collection_web_scraping

<h3>Web Scraping Mars News and Weather Data</h3>
<hr/>
<p>
This assignment is to use web scraping technique to extract and extract Mars news and weather data from the articles on the website 
<a>https://static.bc-edx.com/data/web/mars_news/index.html</a>


</p>

<h3>Overview</h3>
<hr/>
<p>
Goal:
<ul>
<li>Scrape titles and preview text from Mars news articls</li>
<li>scrape and analyze Mars weather data, which exists in a table</li>
</ul>

<h3>Tools and Techniques</h3>
<hr/>

<ul>
<li>Python</li>
<li>Jupyter Notebook</li>
<li>Beautiful Soup</li>
<li>Splinter</li>
<li>Pandas</li>
</ul>

<h3>Project Structure</h3>
<hr/>


<h3>Part 1: Mars News Scraping</h3>
<ol>
<li>Used automated browsing with Splinter to visit the Mars news site.</li>
<li>Created a Beautiful Soup object to parse the HTML content.</li>
<li>Extracted the titles and preview text of the news articles.</li>
<li>Stored the scraping results in a list of dictionaries with 'title' and 'preview' keys.</li>
<li>Printed the list in the Jupyter Notebook.</li>
<li>Optionally, stored the scraped data in a JSON file for easier sharing.</li>
</ol>

<h3>Part 2: Mars Weather Data Scraping and Analysis</h3>
<ol>
<li>Used automated browsing with Splinter to visit the Mars Temperature Data Site.</li>
<li>Created a Beautiful Soup object to scrape the data in the HTML table.</li>
<li>Assembled the scraped data into a Pandas DataFrame with appropriate column headings.</li>
<li>Examined and cast the data types to appropriate datetime, int, or float data types if necessary.</li>
<li>Analyzed the dataset to answer questions related to Martian months, days, temperature, and atmospheric pressure.</li>
<li>Visualized the results using bar charts and line plots.</li>
<li>Exported the DataFrame to a CSV file.</li>
</ol>

<h3>Conclusion</h3>
<hr/>
<p>
This assignment showcased the effective use of web scraping to gather and analyze data from Mars-related websites, yielding valuable insights into Martian months, days, temperature, and atmospheric pressure.
</p>