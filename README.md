# Spain-Job Market Insights

This code represents Spain job offers analysis based on Linkedin information.
Information has been scraped from Linkedin publica page and after cleaning represented on tableau.
Workflow steps:

1.	Scraping 103k jobs from Linkedin, via Selenium and Random user method. Files used: Main and Myfunction.
2.	More than 150 scrap links had to be used to have all the jobs since Linkedin has a limitation of 1k jobs in each scraping session. Files used: Main and Myfunction.
3.	Every 1k jobs takes 5mintues to be scrapped.
4.	After scraping the date, duplicated had been dropped. File: Data-preanalysis
5.	Next step was to clean cities, 8000 city names changed to 17 communities. File: location cleaning.
6.	Next Step cleaning job titles, more than 36k titles was cleaned to aprox 100 jobs. File: Title cleaning.
7.	Then job function column was added based on job title. Files: Final Cleaning.
8.	To finish a zoom was made on data jobs to have deeper analysis on that. Files: Data Deep dive and Data Data Cleaning.
9.	Finally, information was represented on tableau.
