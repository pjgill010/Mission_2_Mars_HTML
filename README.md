##Mission_2_Mars_HTML

#Assignment
- Deliverable 1: Scrape titles and preview text from Mars news articles.
- Deliverable 2: Scrape and analyze Mars weather data, which exists in a table

#Part 1
- Automated browsing used for Mars News site
- Beautiful Soup object created, used to extract the title/preview of Mars news articles

#Part 2:
- Automated browsing used to visit Mars Temperature Data Site, created Beautiful Soup object to extract elements
- Assembles scraped data in Pandas DataFram with the columns matching table on website
- Pandas functions were used to answer following questions:

1. How many months exist on Mars? 12
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset? 1867
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
- Find the average minimum daily temperature for all of the months
- Plot the results as a bar chart

![avglowtemp](https://user-images.githubusercontent.com/118948437/230698379-11041b06-1dbd-477e-a739-e09986fcbdfb.png)

4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
- Find the average daily atmospheric pressure of all the months
- Plot the results as a bar chart

![avgmnthpressure](https://user-images.githubusercontent.com/118948437/230698430-5f25e55d-fde4-40cb-95b8-47515bed77c0.png)

5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
- Consider how many days elapse on Earth in the time that Mars circles the Sun once
- Visually estimate the result by plotting the daily minimum temperature

![mintemp_v_earthdays](https://user-images.githubusercontent.com/118948437/230698471-58c52abb-e90f-49a5-bdee-33275bc67b00.png)

6. Export the DataFrame to a CSV file - found in output folder
