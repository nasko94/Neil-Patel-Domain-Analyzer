# Neil-Patel-Domain-Analyzer

Automate domain analysis using Neil Patel's API for SEO and digital marketing insights.

[See what it does here <- VIDEO](https://www.awesomescreenshot.com/video/29318234?key=f38992165be318bfa9208116f2ea79ae)

```Note: The script is currently not included here. If you want to use it, text me on``` [WhatsApp](https://wa.me/359893968378)

## Description

This Node.js script streamlines the process of gathering and analyzing domain data from Neil Patel's API. It's an essential tool for digital marketers, SEO professionals, and business analysts looking to quickly assess the online presence and potential value of multiple domains.

## Features

- Scrapes domain data from Neil Patel's API
- Processes multiple domains from a CSV file
- Implements proxy rotation for improved reliability and rate limit avoidance
- Calculates additional metrics and assigns a status score to each domain
- Outputs comprehensive results to a CSV file

## Key Metrics Analyzed

- Organic Monthly Traffic
- Organic Keywords
- Domain Authority
- Backlinks
- Referring Domains
- Follow/No Follow Links
- Current Month Search Traffic
- 3-Month Traffic Trend
- Top Tier Keywords Growth

## Installation

```bash
git clone https://github.com/nasko94/Neil-Patel-Domain-Analyzer.git
cd Neil-Patel-Domain-Analyzer
npm install
```


## Setup

1. Create domains.csv in the project root:
   - Include a header row with "domain" as the column name
   - List domains to analyze, one per row

2. Create proxies.txt in the project root:
   - List proxies, one per line, in the format: ip:port:username:password

## Usage

Run the script:

bash
node scraper.js


The script processes each domain, fetches data from Neil Patel's API, calculates metrics, and outputs results to results.csv.

## Output

The results.csv file includes:

- Domain
- Organic Monthly Traffic
- Organic Keywords
- Domain Authority
- Backlinks
- Referring Domains
- Follow Links
- No Follow Links
- Current Month Search Traffic
- 3-Month Traffic Trend
- Top Tier Keywords Growth
- Status (Bad, Good, or Excellent)
- Score (Numerical value determining the status)

## Scoring System

Domains are evaluated using a point-based system:

- Traffic: 0-30 points
- Domain Authority: 0-20 points
- Backlinks and Referring Domains: 0-20 points
- Traffic Trend: 0-20 points
- Top Tier Keywords Growth: 0-10 points

Total scores are categorized as:
- Excellent: 80-100 points
- Good: 50-79 points
- Bad: 0-49 points

## Use Cases

1. Competitive Analysis
2. Link Building
3. Content Marketing
4. M&A Research
5. Affiliate Marketing

## Limitations

- Depends on access to Neil Patel's API
- Requires a list of working proxies
- Analysis based on available metrics may not capture all aspects of a domain's value

## Contributing

Contributions, issues, and feature requests are welcome! Check out our [issues page](https://github.com/yourusername/neil-patel-domain-analyzer/issues).

## License

This project is [MIT](https://choosealicense.com/licenses/mit/) licensed.
