## Final Project for GLBL 6060 Applied Python for Global Affairs

### Shuzhe(Rosemary) Zhang and Yirui Zhao

Folder Description:

The **Raw** folder contains the raw information we web-scrape from the AEA website.

The **Derived** folder contains the intermediate CSV files generated after the data cleaning process.

Each code has the functionality as follows:

- **0 AEA-Paper-Database.ipynb**: In this script, we utilize web scraping techniques to gather information such as authors, abstracts, JEL codes, issues, and article titles from the AER website at https://www.aeaweb.org/journals. We include the following journals:
  - American Economic Review (AER) from Volume 89 to the present: https://www.aeaweb.org/journals/aer
  - AER: Insights from Volume 1 to the present: https://www.aeaweb.org/journals/aeri
  - AEJ: Applied Economics from Volume 1 to the present: https://www.aeaweb.org/journals/app
  - AEJ: Economic Policy from Volume 1 to the present: https://www.aeaweb.org/journals/pol
  - AEJ: Macroeconomics from Volume 1 to the present: https://www.aeaweb.org/journals/mac
  - AEJ: Microeconomics from Volume 1 to the present: https://www.aeaweb.org/journals/mic

**Note**: To run this script, you will need to install the packages selenium and pandas. Additionally, ensure you have the appropriate WebDriver installed.

Last Update: 2024-03-15
