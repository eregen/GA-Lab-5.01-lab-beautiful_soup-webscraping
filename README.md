# Web Scraping with Beautiful Soup

Using Beautiful Soup, I scrape [ChubbyGrub.com](http://chubbygrub.com), and create a DataFrame of food items from every restaurant. The DataFrame looks like this:

| restaurant | category | name    | calories | carbs | fat |
|------------|----------|---------|----------|-------|-----|
| McDonald's | Burgers  | Big Mac | 540      | 45    | 29  |
| Burger King | Burgers  | Whopper | 900      | 51    | 57  |
| ... | ...  | ... | ...      | ...    | ...  |
| Chili's | Ribs  | Shiner Bock® BBQ Ribs | 2310      | 168    | 123  |


I use the code from the web scrapping lesson to gather the data, then I wrote a nested for loop to create a food list for every entry in the restaraunt list where the desired table entry is selected and unnecessary text is split away.  I then convert to a DataFrame and output it.
