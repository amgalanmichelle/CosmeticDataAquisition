AI Usage Report

What Worked Well

AI was useful for helping generate code to import data, explore datasets and troubleshoot technical issues. It also helped explain how to structure the project and use GitHub effectively.

AI was useful for generating Python code to import and explore the Kaggle dataset using Pandas. It helped identify suitable functions for analysing the dataset structure, including viewing column names, checking data types, generating summary statistics and identifying missing values.

AI was also useful during the web scraping stage. It helped generate code using Requests, BeautifulSoup and Regular Expressions to extract product names, brands, ratings and review counts from the Ulta Beauty website. This significantly reduced the time needed to investigate the webpage structure and extract relevant data.

AI was effective when troubleshooting errors encountered during the project, such as Python environment issues, DataFrame creation errors and problems caused by arrays having different lengths.

What Worked Poorly

Some generated code required adjustment to match the dataset structure. It was important to understand and test all generated code before using it.

AI-generated code did not always work correctly on the first attempt because the structure of the Ulta Beauty webpage was more complex than expected. Several regular expression patterns needed to be modified before the correct product information could be extracted.

Some suggested code returned irrelevant results because the webpage contained a large amount of JavaScript and website metadata. Manual inspection of the page source was required to identify the correct fields containing product names, brands, ratings and review counts.

AI occasionally provided solutions that required further adjustment to match the specific structure of the dataset and website. Therefore, it was important to understand and test all generated code rather than using it without verification.


Prompts Used

Give Outline of the project  

Which website out of boots, space nk, Sephora would be the best for data scraping 

How to right click to inspect the webpage on a mac 

Give list of US beauty websites 

What does 404 mean after i ran this code 

url = "https://www.ulta.com/shop/body-care/suncare/sunscreens"

headers = {
    "User-Agent": "Mozilla/5.0"
}

response = requests.get(url, headers=headers)

print(response.status_code)



