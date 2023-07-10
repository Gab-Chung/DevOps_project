# Web Crawler

## Extract links Project
This is a Python script that implements a web crawler. It allows you to crawl a given URL and extract links from the page. The script recursively follows the links within the same domain up to a specified maximum depth threshold.

## To run the script, you need to provide the following command-line arguments:
- -u or --url: The start URL for crawling.
- -t or --threshold: The recursion depth threshold (optional).
- -o or --output: The name of the output file (optional).
- -s or --simple: Simplify the results (optional).
- -e or --ext_sort: Sort the external links based on extension (optional).

## Requirements:
- Install [python]('https://www.python.org/downloads')
- Install requests and beautifulsoup4 with the below command:
```
pip install requests beautifulsoup4
```

## An example of the command to run the script:

```
python web_crawler.py -u [url] -t 3 -o output.txt -s -e

python web_crawler.py -u https://www.lego.com -t 3 -o output.txt -s -e
```

**Note**: In the above example, the script will crawl the https://www.lego.com URL up to a depth of 3. The results will be saved in the output.txt file. The output will be simplified, and the external links will be sorted based on their extensions. And this might take a lot of time to completely run, depending on your internet connection.
