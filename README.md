## Final Project for GLBL 6060 Applied Python for Global Affairs

### Shuzhe(Rosemary) Zhang and Yirui Zhao

#### Folder Description

The **Raw** folder contains the raw information we web-scrape from the AEA website.

The **Derived** folder contains the intermediate CSV files generated after the data cleaning process.

Each code has the functionality as follows:

-   **0-Database.ipynb**: In this script, we utilize web scraping techniques to gather information such as authors, abstracts, JEL codes, issues, and article titles from the AER website at <https://www.aeaweb.org/journals>. We include the following journals:
    -   American Economic Review (AER) from Volume 89 to the present: <https://www.aeaweb.org/journals/aer>
    -   AER: Insights from Volume 1 to the present: <https://www.aeaweb.org/journals/aeri>
    -   AEJ: Applied Economics from Volume 1 to the present: <https://www.aeaweb.org/journals/app>
    -   AEJ: Economic Policy from Volume 1 to the present: <https://www.aeaweb.org/journals/pol>
    -   AEJ: Macroeconomics from Volume 1 to the present: <https://www.aeaweb.org/journals/mac>
    -   AEJ: Microeconomics from Volume 1 to the present: <https://www.aeaweb.org/journals/mic>
-   **1-Dashboard.ipynb**: In this script, we build up our dashboard.

#### Installation Requirements

To run the script, install the following Python packages:

``` bash
pip install selenium pandas numpy requests beautifulsoup4 panel hvplot spacy sentence-transformers bertopic scikit-learn openai
```

Additionally, you'll need to download and set up the appropriate WebDriver for your browser for Selenium to work. After installing SpaCy, download a language model with:

``` bash
python -m spacy download en_core_web_sm
```

Ensure you have the necessary WebDriver installed for Selenium operations. Ensure you have your ChatGPT API key stored on your computer.

Last Update: 2024-4-11
