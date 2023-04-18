# data-extraction-challenge

<strong>Module 11 Data Extraction challenge for Data Analytics Bootcamp</strong>

<strong>FILES</strong>
<ul>
<li>part_1_mars_news.ipynb (<em>File</em>)
<li>part_2_mars_weather.ipynb (<em>File</em>)
<li>terr_dates_df.csv (<em>File</em>)
<li>weather_df.csv (<em>File</em>)
<li><strong>.ipynb_checkpoints (<em>Directory</em>):</strong>
<ul>
<li>part_1_mars_news-checkpoint.ipynb (<em>File</em>)
<li>part_2_mars_weather-checkpoint.ipynb (<em>File</em>)
</ul>
</ul>
<br>
<strong>REQUIREMENTS</strong>
<ul>
<li><strong>Part 1: Scrape Titles and Preview Text from Mars News (40 points)</strong>
  <ul>
  <li>Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). (10 points)
  <li>The titles and preview text of the news articles were scraped and extracted. (20 points)
  <li>The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries. (10 points)</ul></ul>

<ul>
<li><strong>Part 2: Scrape and Analyze Mars Weather Data (60 points)</strong>
  <ul>
  <li>The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types. (15 points)
  <li>The data was analyzed to answer the following questions: (10 points)
    <ul>
    <li>How many months exist on Mars? (5 points)
    <li>How many Martian days' worth of data are there? (5 points)</ul>
  <li>The data was analyzed to answer the following questions, and a data visualization was created to support each answer: (30 points)
    <ul>
    <li>Which month, on average, has the lowest temperature? The highest? (10 points)
    <li>Which month, on average, has the lowest atmospheric pressure? The highest? (10 points)
    <li>How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. (10 points)</ul>
  <li>The DataFrame was exported into a CSV file. (5 points)</ul>
