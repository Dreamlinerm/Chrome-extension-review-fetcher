# Extension Review Fetcher

This script allows you to fetch all reviews of your extension from the chrome marketplace.

## Steps to Use

1. Install python package: `pip install beautifulsoup4 requests`
2. Run the Python script with your extension url as an argument. For example, `python reviewFetcher.py https://chromewebstore.google.com/detail/streaming-enhanced-netfli/akaimhgappllmlkadblbdknhbfghdgle`

After these steps, the script will fetch all reviews in all languages and save them in an HTML file for your convenience.

## Output

The output will be an HTML file containing all the reviews of your extension. You can open this file in any web browser to view the reviews.