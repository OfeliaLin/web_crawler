# Image Scraper

## Overview

This repository contains a Python script for scraping images from the Fossil website. It utilizes Selenium and BeautifulSoup libraries to navigate through the website and extract image URLs.

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your_username/fossil-image-scraper.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Ensure that you have Google Chrome installed on your system.

## Usage

1. Prepare a text file (`input_file.txt`) containing a list of URLs from the Fossil website.
2. Run the script:

    ```bash
    python scraper.py
    ```

3. The script will start downloading images from each URL and save them to the specified output directory.

## Configuration

- You can customize the output directory by modifying the `out_dir` variable in the script.
- Adjust the `DIV` variable to match the specific HTML element containing the image links if necessary.

## Contributors

- [Your Name](https://github.com/your_username) - Creator and maintainer

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
