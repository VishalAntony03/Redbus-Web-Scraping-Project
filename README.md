Redbus Data Scraping and Filtering with Streamlit Application
This project is centered around extracting, storing, and visualizing real-time data from the Redbus website. The primary goal is to scrape bus route information, pricing, and availability details using Selenium, then store the data in a structured format within a MySQL database. The project further enhances data accessibility and interactivity by providing a clean, user-friendly interface through Streamlit, where users can filter and view the scraped data.

The workflow is divided into three key phases:

Data Scraping: Using Selenium WebDriver, we automate the extraction of bus route data from the Redbus website. This part of the project is managed within a Jupyter Notebook, allowing for iterative development and testing. Selenium WebDriver is set up to interact with the website dynamically, simulating real user behavior to collect route links, bus names, types, timings, prices, and availability data.

Data Storage: Once the data is collected, it is stored in a MySQL database for efficient querying and long-term access. The MySQL database ensures that the scraped data is well-organized and easily retrievable. SQL queries are used to create tables and manage the data within the database.

Data Visualization: Finally, the data is visualized using a custom-built web application created with Streamlit. Streamlit offers an intuitive platform to build interactive dashboards, allowing users to filter bus routes based on various criteria, such as price, availability, or duration. The visualization tool is developed and maintained in Visual Studio Code (VS Code), ensuring a smooth and responsive user experience.

Tools and Technologies:
Python 3.x: The primary language used for data scraping, database operations, and building the Streamlit application.
Selenium WebDriver: For automating the extraction of data from the Redbus website via a Chrome browser.
Jupyter Notebook: Used for developing and testing the data scraping process, making it easy to visualize and debug.
MySQL Server: The database system where the scraped data is stored and managed.
Streamlit: The web framework used to create an interactive interface for visualizing and filtering bus data.
Visual Studio Code (VS Code): The integrated development environment (IDE) used for coding the Streamlit application and managing the project files.
Chrome Web Browser: Selenium WebDriver interacts with the Redbus website using Chrome for scraping.
For a more detailed explanation of each phase and further instructions on setting up the project, refer to the project illustration attached in the main repository file.
