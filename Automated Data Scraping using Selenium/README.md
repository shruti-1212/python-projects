# Automated Data Scraping using Selenium
This Python project leverages the Selenium library for automating web scraping tasks, including navigation between pages, form submissions (such as login credentials), and link clicking. In addition to the core data scraping functionality, Selenium is employed to automate various steps necessary to reach the target pages for data extraction. The primary focus of this project is to scrape job offers and gather relevant information from 14 pages, each containing 25 job offers.

# Automated Steps
- Navigate to the LinkedIn login page.
- Identify and interact with the cookies pop-up, by clicking on the "Accept cookies" button.
- Provide login credentials (E-Mail Address and Password) and click the Login button.
- Access the Jobs section from the navigation menu.
- Search for job positions related to Junior Data Analyst in Spain.
- Scroll down through the page, collecting the links for each displayed job offer.
- Move to the next page as needed, continuing to collect job offer links.
- Once all links are gathered, visit each link individually.
- Click the "See More" button to expand the job description text.
- Perform data scraping on the desired information.

This automation script streamlines the process of extracting job-related data from LinkedIn, saving time and effort by automating repetitive tasks involved in navigating and gathering information from multiple pages.
