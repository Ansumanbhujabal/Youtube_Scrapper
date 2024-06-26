
### README.md

```markdown
# YouTube Scraper 🎥


## Overview
YouTube Scraper is an open-source tool designed to scrape video titles and URLs from a specified YouTube channel.
The data is then exported into an Excel file for easy access and analysis. This tool uses Python and integrates with Selenium
for web scraping and Streamlit for an interactive user interface.

## Features
- Scrapes video titles and URLs from any YouTube channel
- Outputs data to an Excel file
- User-friendly interface with Streamlit
- Easy setup and configuration

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Ansumanbhujabal/Youtube_Scrapper.git
   cd Youtube_Scrapper
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv myenv
   source myenv/bin/activate  # On Windows use `myenv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

2. Open your web browser and go to the provided local URL (e.g., `http://localhost:8501`).

3. Enter the YouTube channel URL and the desired name for the output Excel file, then click "Get Video Links".

4. Download the generated Excel file with the video links.

## Tools Used
- ![Python](https://img.shields.io/badge/Python-3.8%2B-blue) [Python](https://www.python.org/)
- ![Selenium](https://img.shields.io/badge/Selenium-WebDriver-brightgreen) [Selenium](https://www.selenium.dev/)
- ![Streamlit](https://img.shields.io/badge/Streamlit-Framework-red) [Streamlit](https://streamlit.io/)
- ![Openpyxl](https://img.shields.io/badge/Openpyxl-Excel-yellow) [Openpyxl](https://openpyxl.readthedocs.io/)
- ![Webdriver Manager](https://img.shields.io/badge/Webdriver%20Manager-Install-orange) [Webdriver Manager](https://github.com/SergeyPirogov/webdriver_manager)

## Contribution
Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

[Github](https://github.com/Ansumanbhujabal) | [LinkedIn](https://www.linkedin.com/in/ansuman-simanta-sekhar-bhujabala-30851922b/) | © 2024 Ansuman Bhujabala
```
