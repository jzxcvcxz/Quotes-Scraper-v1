# Quotes Scraper v1
Welcome to **Quotes Scraper v1**. This is a web scraping tool that extracts quotes from the **Quotes to Scrape** website (https://quotes.toscrape.com/). Using Python and Selenium, with a single command, this scraper will log in to the website, gather information (author, quote, the link to the author's individual about page, and tags) of the top 20 quotes, and save them in a structured JSON format.

Here is the sample output for Quotes Scraper v1:
```
[
  {
    'author': 'Albert Einstein',
    'quote': 'The world as we have created it is a process of our thinking. It cannot be changed without changing our thinking.',
    'author_link': 'https://quotes.toscrape.com/author/Albert-Einstein',
    "tags": ["change", "deep-thoughts", "thinking", "world"]
  },
  {
    'author': 'J.K. Rowling',
    'quote': 'It is our choices, Harry, that show what we truly are, far more than our abilities.',
    'author_link': 'https://quotes.toscrape.com/author/J-K-Rowling',
    "tags": ["abilities", "choices"]
  },
  //more quotes
]

```
For another output format, please refer to https://github.com/jzxcvcxz/Quotes-Scraper-v2.

Please follow these steps to set up and run Quotes Scraper v1:

**1. Clone this repository:**
```
git clone https://github.com/jzxcvcxz/Quotes-Scraper-v1.git
```


**2. Install Selenium:**
```
pip install selenium
```

**3. Execute Quotes Scraper v1:**
```
python quotes_scraper_v1.py
```
The extracted quotes will be saved in **quotes-v1.json** in the same directory as the code.
