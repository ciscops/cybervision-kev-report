# CyberVision KEV Report

This python script utilizes CyberVision's CVE (Common Vulnerabilities and Exposures) report and identifies the KEVs (Known Exploited Vulnerabilities), outputting them to an html file for easy readibility. This allows the customer to prioritize which vulnerabilities to patch as KEVs have a higher importance from CVEs.

## Steps
1. Download this repository as a zip file
2. Unzip the file and place your CyberVision CVE report in this folder
3. Download the latest Known Exploited Vulnerabilities Catalog (**CSV version**) [here](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)
4. Move this csv file into that same folder from above
5. Run the following command (after replacing "[filename]" with the filename of your CyberVision CVE report along with the extension ".xlsx")
    ```python find-kevs.py [filename]```
6. Open the ```kev-report.html``` file in your browser to view the results

**Note:** You will need to have Python (and the pandas and openpyxl libraries) installed on your device. To download Python, follow [these instructions](https://www.python.org/downloads/).