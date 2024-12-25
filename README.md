# Web-Scraping-Multiple-Page-Using-Python
Extract data and content from an online store

The Purpose of this project is to scraping data from multiple page online store and load it to csv file. Using several libraly of Python such as pandas, Requests and BeautifulSoup.
We scraping the online store website. Filter it for Iphone Product with 3 star Above.

Please check the python file for better understanding.

# Prerequisite
1. Use Jupyter Notebook
2. Os Ubuntu 20
3. install library using pip install for requests, BeautifulSoup and pandas
   

# Lessons from this Project
1. Install and Import Library needed.
2. Knowledge of html language.
3. inspect the website.
4. Keep the class or div class value for specific text.
5. discover the text do you want to take. For this project we will find Title, Price, Description, Total Rating and reviews and Rating star of iphone at flipkart online store.
6. Define an empty variable for append the looping data.
7. Create looping for get request to multiple page. We get for 10 pages.
8. print using BeautifulSoup for better format text.
9. find the class, Paragraph, and Attribute of the text.
10. Transform to the good format.
11. save the looping result to dataframe pandas.
12. export or save the result df.to_csv.
