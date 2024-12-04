# Web Scraping Project: 
Largest Companies in the United States by Revenue

## Overview
This project involves scraping data from the Wikipedia page listing the largest companies in the United States by revenue. The data can be used for analysis, visualization, or other purposes.

## Requirements
To run this project, you'll need the following Python libraries:
- `requests`
- `beautifulsoup4`

You can install these libraries using pip:

```bash
pip install requests beautifulsoup4
```

## Usage
1. **Clone the repository** (if applicable):
   ```bash
   git clone https://github.com/nisch-mhrzn/Scraping.git
   cd Scraping
   ```
2. **Data Extraction**:
   The script fetches the HTML content from the specified Wikipedia URL and parses it to extract relevant information about the largest companies.

## Code Explanation
The main components of the script include:

- **Fetching the page**:
  ```python
  url = 'https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue'
  page = requests.get(url)
  ```

- **Parsing the HTML**:
  ```python
  soup = BeautifulSoup(page.text, 'html')
  ```



