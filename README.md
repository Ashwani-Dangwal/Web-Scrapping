# Web-Scrapping
This is a web scraping project that aims to extract quotes, names, and tags from the website https://quotes.toscrape.com using the libraries Requests, Beautiful Soup, and Pandas. The code includes two functions, "scrape_quotes" and "save_as_csv", which are responsible for downloading and parsing the webpage, extracting the relevant information, and saving the results in a CSV file.

The "scrape_quotes" function uses a while loop to iterate over the pages of the website until it reaches the end, at which point it calls the "save_as_csv" function to create a CSV file with the extracted information. The "save_as_csv" function converts the extracted information into a Pandas dataframe and saves it as a CSV file.

The code also includes a second version of the "scrape_quotes" function, called "scrape_quotes_new", which uses a for loop instead of a while loop. The "scrape_quotes_new" function extracts the relevant information from a list of quotes passed as an argument and returns the extracted information as separate lists of quotes, authors, and tags. The "save_as_csv_new" function is then used to convert and save the information as a CSV file.

Both versions of the code output the same result and take approximately the same time to execute
