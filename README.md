# Web Scraping Projects

This repository contains various web scraping projects that demonstrate techniques for extracting data from different websites. Each project focuses on specific platforms, including job boards, book retailers, e-commerce sites, educational resources, and sports websites.

## Overview

The projects in this repository showcase practical examples of web scraping across a range of domains, providing valuable data for analysis, research, and application development.

## Projects

### 1. [Wuzzaf Job Listings Scraper](./wuzzaf_job_listings_scraper)

**Description**: Scrapes job listings from Wuzzaf, a popular job board in the MENA region. This scraper collects detailed job information including titles, companies, locations, and job descriptions.

**Key Features**:
- **Target Website**: Wuzzaf.
- **Data Fields**: Job title, company name, location, job description, posting date.
- **Techniques**: Handling job listing pages, pagination, and data extraction.

**Technologies Used**:
- **BeautifulSoup**: For parsing job listing HTML.
- **Requests**: For making HTTP requests to Wuzzaf.
- **Pandas**: For data manipulation and saving to CSV.

**Usage**:
1. Configure the scraper with Wuzzaf job board URLs.
2. Run the script to collect job listings data.
3. Analyze the data to identify job market trends in the MENA region.

### 2. [Diwan Books Scraper](./diwan_books_scraper)

**Description**: Extracts book information from Diwan Books, a well-known book retailer. The scraper gathers details such as book titles, authors, prices, and publication dates.

**Key Features**:
- **Target Website**: Diwan Books.
- **Data Fields**: Book title, author, price, publication date, and ISBN.
- **Techniques**: Parsing book details from product pages and handling multiple pages.

**Technologies Used**:
- **BeautifulSoup**: For parsing book information.
- **Requests**: For fetching book pages from Diwan Books.
- **Pandas**: For organizing and exporting data.

**Usage**:
1. Customize the scraper with Diwan Books URLs.
2. Execute the script to gather book data.
3. Use the collected data for market analysis or book recommendations.

### 3. [eBay Product Scraper](./ebay_product_scraper)

**Description**: Scrapes product listings from eBay, including details such as product names, prices, ratings, and seller information. This scraper is designed for e-commerce research and competitive analysis.

**Key Features**:
- **Target Website**: eBay.
- **Data Fields**: Product name, price, rating, number of reviews, seller.
- **Techniques**: Handling dynamic content, pagination, and product detail extraction.

**Technologies Used**:
- **Selenium**: For automating browser interactions and handling dynamic content.
- **BeautifulSoup**: For parsing product information.
- **SQLite**: For storing collected data.

**Usage**:
1. Configure the script with eBay product search URLs.
2. Run the scraper to collect product data.
3. Analyze the data to assess market trends and competitive positioning.

### 4. [MIT Courses Scraper](./mit_courses_scraper)

**Description**: Extracts information about courses from MIT's online course catalog. The scraper collects details such as course titles, descriptions, instructors, and available terms.

**Key Features**:
- **Target Website**: MIT OpenCourseWare.
- **Data Fields**: Course title, description, instructor, term, and URL.
- **Techniques**: Parsing course catalog pages and handling various course listings.

**Technologies Used**:
- **Requests**: For fetching course catalog pages.
- **BeautifulSoup**: For parsing course details.
- **Pandas**: For storing and exporting data.

**Usage**:
1. Update the scraper with MIT OpenCourseWare URLs.
2. Execute the script to gather course information.
3. Use the data for academic research or course analysis.

### 5. [Yalla Kora Sports Scraper](./yalla_kora_scraper)

**Description**: Scrapes sports news and match results from Yalla Kora, a sports news website. The scraper collects data on sports events, scores, and team performance.

**Key Features**:
- **Target Website**: Yalla Kora.
- **Data Fields**: Match results, scores, team names, and event dates.
- **Techniques**: Handling live scores, match updates, and historical data.

**Technologies Used**:
- **BeautifulSoup**: For parsing sports news and match details.
- **Requests**: For making HTTP requests to Yalla Kora.
- **Pandas**: For organizing and analyzing sports data.

**Usage**:
1. Configure the scraper with Yalla Kora URLs.
2. Run the script to collect sports news and match results.
3. Analyze the data to track sports trends and team performance.

## Installation

To run these web scraping projects, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/youssefa7med/Web_Scraping.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd Web_Scraping
   ```
3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Desired Project**:
   - Navigate to the specific project directory and execute the corresponding script:
     ```bash
     cd project_directory
     python script_name.py
     ```

## Contributing

Contributions are welcome! If you have suggestions for improvements, additional scraping targets, or new features, please fork the repository, make your changes, and submit a pull request.

## License

This repository is licensed under the MIT License. For more details, please refer to the [LICENSE](LICENSE) file.

## Acknowledgments

Special thanks to the open-source community for providing the tools and libraries that facilitated these web scraping projects. Your contributions are essential to advancing the field of data extraction and analysis.
