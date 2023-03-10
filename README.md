# HTML-challenge

This code accomplished two goals: to scrape the mars news landing page for article titles and article previews and to scrape the of mars curiosity rover data and analyze it.

## Methods

- Use splinter and beautiful soup to scrape html
- Loop through scraped html to extract article titles and previews

- Use pandas to read the html into a DataFrame
- Convert data types when relevant
- Find highest and lowest temperatures grouped by month and plot
- Find highest and lowest pressures grouped by month and plot
- Plot minimum temperatures and use peak to peak to determine the approximate length of a Martian year in Earth days

## Results

The results of the article title and preview scrape are as follows:
![image](https://user-images.githubusercontent.com/118322354/224399430-d2178573-81b0-4a14-b5cf-a59e7a72fdac.png)

The following is what the mars curiosity rover data dataframe looks like:
![image](https://user-images.githubusercontent.com/118322354/224399712-5e7e277c-5683-4305-9b50-53e1f7ee20b3.png)

The coldest month on Mars is month three and the hottest month is month 8. The bar plot of the average temperatures by month is as follows:
![image](https://user-images.githubusercontent.com/118322354/224400140-3c8b49fc-07c4-4912-bd2b-345f8cf07e05.png)

The lowest average pressure occurs in month 6 and the highest occurs in monthe 9 on mars. The plot of that data is as follows:
![image](https://user-images.githubusercontent.com/118322354/224400343-a982b9d6-7ea2-4167-a65b-44e81f3d9c1c.png)

Based on the low temperatures from peak to peak, a Martian year is approximately 661 to 672 Earth days long. This is quite close the actual length of 687 days. The graph of the temperature data by date is as follows:
![image](https://user-images.githubusercontent.com/118322354/224400950-acc46791-033a-48b3-9af8-35a572fdbd4f.png)
