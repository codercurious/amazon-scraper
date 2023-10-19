# Amazon Scraper - Products and bestseller ranks
Interested in using this scraper? Get it here: [Amazon Scraper - Products and bestseller ranks](https://apify.com/curious_coder/amazon-scraper?fpr=ve081&fp_sid=github_amazon-scraper)
## Amazon Product Scraper Overview

Extract product data seamlessly from Amazon using any product listing URLs.  Get critical information like ratings, bestseller ranks, pricing, variations, etc

Here are some examples of URLs supported:

https://www.amazon.com/s?i=specialty-aps&bbn=16225007011&rh=n%3A16225007011%2Cn%3A1292115011

https://www.amazon.in/s?k=redmi&rh=n%3A1389401031&ref=nb_sb_noss

You can also scrape data directly through an API, eliminating the need to access the Apify platform.

## Benefits of Scraping Amazon
- Gain insights into category and subcategory performance.
- Benchmark your products by analyzing emerging brands and their metrics like views and reviews.
- Refine your advertising strategies.
- Leverage Amazon data for competitive advantage.

## Amazon Product Scraper's Capacity
While the scraper can fetch over 100,000 results on average, various factors might affect the output. The actual number of results can be influenced by the input's complexity, the website's internal constraints, and geographical considerations. For accurate results tailored to your needs, consider a test run.

## Cost Implications
Scraping costs can vary based on the data volume and complexity. For a clear estimate, initiate a test scrape with minimal input. This will give you a price-per-scrape which can be scaled as per your requirements. Consider premium plans for cost savings.

## Input Guidelines for the Scraper
When initializing the Amazon Product Scraper, configure your preferences. Inputs can be provided as JSON or directly on the Apify platform. Be mindful of certain nuances while using the scraper, such as potential price variations based on proxy locations.

## Sample of amazon products scraper
```json
 {
    "asin": "B0B5B6R5JN",
    "badges": "",
    "image": "https://m.media-amazon.com/images/I/61ECeMoaOKL._AC_UY218_.jpg",
    "link": "https://www.amazon.com/Prodentim-Advanced-Formula-Probiotic-Supplement/dp/B0B5B6R5JN/ref=sr_1_10?m=A5T7BUI9KCCPB&qid=1693035039&s=merchant-items&sr=1-10",
    "title": "Prodentim Advanced Formula Probiotic Supplement Pills (1 Pack)",
    "stars": 3.4,
    "ratingsCount": 800,
    "priceCurrency": "$",
    "priceAmount": 28,
    "isPrime": false,
    "isSponsored": false,
    "seller": {
      "url": "https://www.amazon.com/S-O-Labs/b/ref=bl_dp_s_web_23450631011?ie=UTF8&node=23450631011&field-lbr_brands_browse-bin=S.O+Labs",
      "name": "S.O Labs"
    },
    "questionsCount": "10",
    "amazonsChoiceKeywords": [],
    "productOverview": [],
    "features": [],
    "bestSellersRank": [
      {
        "rank": "23668",
        "categoryName": "Health & Household",
        "link": "/gp/bestsellers/hpc/ref=pd_zg_ts_hpc"
      },
      {
        "rank": "958",
        "categoryName": "Blended Vitamin & Mineral Supplements",
        "link": "/gp/bestsellers/hpc/3773931/ref=pd_zg_hrsr_hpc"
      }
    ],
    "technicalDetails": [],
    "productDetails": [
      {
        "name": "PackageDimensions‏",
        "value": "4.13 x 1.97 x 1.93 inches; 1.76 Ounces"
      },
      {
        "name": "DateFirstAvailable‏",
        "value": "July 7, 2022"
      },
      {
        "name": "Manufacturer‏",
        "value": "Lightning Labs"
      },
      {
        "name": "ASIN‏",
        "value": "B0B5B6R5JN"
      }
    ],
    "variationValues": {
      "size_name": [
        "30.0 Servings (Pack of 3)",
        "60.0 Servings (Pack of 2)",
        "60 Count (Pack of 5)",
        "60.0 Servings (Pack of 120)"
      ]
    },
    "variationAsins": [
      {
        "size_name": "0",
        "ASIN": "B0B5B9K4R4"
      },
      {
        "size_name": "2",
        "ASIN": "B0B5B7ZXW2"
      },
      {
        "size_name": "1",
        "ASIN": "B0B5B6ZV9R"
      },
      {
        "size_name": "3",
        "ASIN": "B0B5B6R5JN"
      }
    ]
  },
```

## Integrate Amazon Product Scraper
Easily connect the Amazon Product Scraper with cloud services or web apps via Apify platform integrations. Options include Make, Zapier, Slack, Google Sheets, and more. Use webhooks for instant notifications or actions on specific events.

## Apify API with Amazon Product Scraper
The Apify API offers extensive control over the Apify platform with RESTful HTTP endpoints. Manage, schedule, and run Apify actors, access datasets, monitor performances, and much more. 

## Feedback & Support
Your input helps us enhance our tools. For technical feedback or to report issues, please visit the designated section on the Apify Console.
