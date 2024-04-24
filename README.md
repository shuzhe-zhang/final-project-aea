## Final Project for GLBL 6060 Applied Python for Global Affairs

### Shuzhe(Rosemary) Zhang and Yirui Zhao

#### Folder Description

The **Raw** folder contains the raw information we web-scrape from the AEA website.

The **Derived** folder contains the intermediate CSV files, word embeddings, and topic models generated after the data cleaning process. We save our topic modeling but do not include it on GitHub due to size constraints. You can download it from <https://drive.google.com/file/d/15pH-Wa0zJH4odr3dh3giWvKW6ENJaE26/view?usp=drive_link> and save it in this folder. It is also fine to obtain it by running the code, although this may take some time.

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
pip install numpy pandas pycountry requests beautifulsoup4 networkx matplotlib panel hvplot spacy scikit-learn sentence-transformers bertopic umap-learn openai selenium
```

Additionally, you'll need to download and set up the appropriate WebDriver for your browser for Selenium to work. After installing SpaCy, download a language model with:

``` bash
python -m spacy download en_core_web_sm
```

Ensure you have the necessary WebDriver installed for Selenium operations. Ensure you have your ChatGPT API key stored on your computer.

Last Update: 2024-4-23
