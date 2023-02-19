# **Case Study of Quandl**

## [Overview and Origin](https://blog.revolutionanalytics.com/2013/02/quandl-a-wikipedia-for-time-series-data.html)

Quandl is a platform in the Financial Data Marketplaces & Alternative Data Marketplaces & Platforms area. *Quandl lnc.* was incorporated in Sept 1st, 2011 and headquartered in Canada. Quandl is the premier source for financial, economic, and alternative datasets, serving investment professionals. Quandl has 33 integrations with data vendors such as AlgoSeek and The Applied Research Company. Quandl’s platform is used by over 400,000 people, including analysts from the world’s top hedge funds, asset managers and investment banks.

Quandl was founded by Abraham Thomas and Tammer Kamel. [Abraham Thomas](https://www.crunchbase.com/person/abraham-thomas) is Quandl’s co-founder and Chief Data Officer. An expert data analyst, Abraham handles all data-related operations for Quandl: identification, acquisition, curation, organization and dissemination. Abraham co-founded Quandl after a successful career on Wall Street, where he was the youngest trader at a multi-billion-dollar hedgefund. At this fund, Abraham conceived, designed and executed a number of quantitative data-driven investment strategies while managing a $300m arbitrage portfolio. [Tammer Kamel](https://www.crunchbase.com/person/tammer-kamel) is Quandl’s founder and CEO. Tammer created Quandl to solve a problem he encountered again and again in his 15-year career in finance: the time, effort and resources required to acquire and prepare data for analysis. Tammer programmed the first version of Quandl with the goal of making it easy for anyone to find and use high-qualitydata effectively in their professional decision-making.

Finding and formatting numerical data for analysis in R or Excel or indeed any application is a pain that all real world data analysts know all too well.  The solution to this problem is conceptually obvious: one site with all the world’s data, nicely formatted and documented; an omni-platform. The result is [www.quandl.com](https://demo.quandl.com/) as sort of "search engine" for numerical data.  The idea with Quandl is that you can find data fast.

Quandl has raised a total of CA$20.4M in funding over 4 rounds. Their latest funding was raised on Aug 6, 2018 from a Venture [(1)](https://www.crunchbase.com/organization/quandl/company_financials).

## Business Activities:

Quandl is a platform that offers economic, financial, and alternative datasets to its users. Users can download free data, buy paid data or sell data to Quandl. 
- Core Financial Data. Quandl delivers market data from hundreds of sources via API, or directly into Python, R, Excel and many other tools. Save time and money by getting the data you need in the format you want.
- Alternative Data. Quandl brings undiscovered data from non-traditional publishers to investors seeking unique, predictive insights. Quandl leverages exclusive relationships to deliver these alpha-generating datasets to its customers.

Financial analyst have probably spent weeks of my life trying to find data on the web.  And several more weeks validating, formatting and cleaning the data.  Analysis offers data scientists interesting, intellectually stimulating problems.  But data acquisition, the necessary precursor, offers only tedium and pain.  It's a time vampire. Quandl has built a sort of "universal data parser" which has thus far parsed about 2.8 million datasets. 

Quandl's platform is used by over 400,000 people, including analysts from the world's top hedge funds, asset managers and investment banks. Housands of investment firms and businesses use Quandl every day to power their data-driven strategies. 

Stripe Connect, MuleSoft Anypoint Platform, TrueLayer, and Merge are the most popular alternatives and competitors to Quandl. 

**Quandl's Strengths:**
- Quandl provides an enormous collection of data (over 20 million datasets).
- All datasets are accessible for instantaneous download in any preferred format.
- All datasets on Quandl are accessible through the same API, irrespective of who originally published the data or in what format.
- Data is transparent.
- Datasets are clean and easy to locate.
- Some sections of Quandl are free and open for everyone.
- New data is added every week.
- We can utilize Quandl in many programs (Excel, R, Python, Ruby, MATLAB, and more).
- We can utilize Quandl to sell the data.

**Quandl's Weaknesses:**
- There are many exotic datasets that are not free.
- They provide limited amounts of support while constructing analyses or discovering information.
- Quandl is not much beginner-friendly.
- They do not have real-time or delayed stock price data.
- They do not have a master security list.

The data of Quandl comes in two formats: The first being the Time series and the second being the Tables. The Time series data like FRED is composed of a large number of individual time series where each of them has its Quandl code added on to the main Quandl code. For example, US civilian unemployment rate: FRED/UNRATE. On the contrary, the Table data like SF1 consist of single or multiple tables where each of them has its Quandl code. For example, the Quandl code for the Core US Fundamentals table is SHARADAR/SF1. Quandl offers a wide range of tools for Data Analysis which includes API, Python, R, Excel, Ruby, and many more.

## Landscape:

Quandl is a powerful big data platform that support financial analysis and investment decisions making.

The last decade, of course, was the era of big data. New data sources such as online clickstreams required a variety of new hardware offerings on premise and in the cloud, primarily involving distributed computing — spreading analytical calculations across multiple commodity servers — or specialized data appliances. Such machines often analyze data “in memory,” which can dramatically accelerate times-to-answer. Cloud-based analytics made it possible for organizations to acquire massive amounts of computing power for short periods at low cost. Even small businesses could get in on the act, and big companies began using these tools not just for big data but also for traditional small, structured data.

Along with the hardware advances, the need to store and process big data in new ways led to a whole constellation of open source software, such as Hadoop and scripting languages. Hadoop is used to store and do basic processing on big data, and it’s typically more than an order of magnitude cheaper than a data warehouse for similar volumes of data. Today many organizations are employing Hadoop-based data lakes to store different types of data in their original formats until they need to be structured and analyzed.

Since much of big data is relatively unstructured, data scientists created ways to make it structured and ready for statistical analysis, with new (and old) scripting languages like Pig, Hive, and Python. More-specialized open source tools, such as Spark for streaming data and R for statistics, have also gained substantial popularity. The process of acquiring and using open source software is a major change in itself for established businesses.
The technologies I’ve mentioned for analytics thus far are primarily separate from other types of systems, but many organizations today want and need to integrate analytics with their production applications. They might draw from CRM systems to evaluate the lifetime value of a customer, for example, or optimize pricing based on supply chain systems about available inventory. In order to integrate with these systems, a component-based or “microservices” approach to analytical technology can be very helpful. This involves small bits of code or an API call being embedded into a system to deliver a small, contained analytical result; open source software has abetted this trend.

This embedded approach is now used to facilitate “analytics at the edge” or “streaming analytics.” Small analytical programs running on a local microprocessor, for example, might be able to analyze data coming from drill bit sensors in an oil well drill and tell the bit whether to speed up or slow down. With internet of things data becoming popular in many industries, analyzing data near the source will become increasingly important, particularly in remote geographies where telecommunications constraints might limit centralization of data.

Another key change in the analytics technology landscape involves autonomous analytics — a form of artificial intelligence or cognitive technology. Analytics in the past were created for human decision makers, who considered the output and made the final decision. But machine learning technologies can take the next step and actually make the decision or adopt the recommended action. Most cognitive technologies are statistics-based at their core, and they can dramatically improve the productivity and effectiveness of data analysis.

However, these new tools are also more complex and in many cases require higher levels of expertise to work with. As analytics has grown in importance over the last decade, the commitments that organizations must make to excel with it have also grown. Because so many companies have realized that analytics are critical to their business success, new technologies haven’t necessarily made it easier to become — and remain — an analytical competitor. Using state-of-the-art analytical technologies is a prerequisite for success, but their widespread availability puts an increasing premium on nontechnical factors like analytical leadership, culture, and strategy.

* What are the other major companies in this domain?

## Results

* What has been the business impact of this company so far?

* What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics?

* How is your company performing relative to competitors in the same domain?

## Recommendations

* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)

* Why do you think that offering this product or service would benefit the company?

* What technologies would this additional product or service utilize?

* Why are these technologies appropriate for your solution?
