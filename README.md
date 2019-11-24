# psa-dna-web-scraper
# How to use package


Install dependencies that are needed for the package
# 1.Install Beautiful Soup
    
    pip3 install beautifulsoup4
Source - https://www.crummy.com/software/BeautifulSoup/bs4/doc/#installing-beautiful-soup

# 2. Install requests

    pip3 install requests
# 3. Install psa-dna-web-scraper

    pip3 install psadnawebscraper
    
# How to use in an app


    from psadnawebscraper1 import psa_dna_web_scraper
    app = psa_dna_web_scraper()
    results = app.get_psa_dna_card_data(12345678)
    print(results)


