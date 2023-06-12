# Data Cataloging (GVR_PROD & IS360)

## Purpose
* The creation of this GVR_PROD catalog will help with consolidating information into one place about each table & will aid in data mapping - as you can just copy and paste information from here into the data mapping document.


## Run Code
* Clone GitHub repository and run the code inside of the 'Data_Catalog_Script.ipynb' file
* Change email address located inside of the creds.json file to an appropriate email address
* While running the code, please do not have the Data_Catalog.xlsx open while running the script
* This should produce an output inside of the Catalog/Data_Catalog.xlsx that looks like this:

<p>
  <img 
    src=Photos/catalog_creation.png
  >
</p>

## After Running Code

* Once the catalog sheet has been populated - navigate to here (see photo below) and press 'Filter'

<p>
  <img 
    src=Photos/filter.png
  >
</p>

* Slicers don't stick to the worksheet when something is changed inside of the worksheet so creating them again is a necessity.
    * To do so, click into the pivot table located on the worksheet titled 'Catalog Drill Down' and follow the photo steps shown below:

<p>
  <img 
    src=Photos/slicers.png
  >
</p>

<p>
  <img 
    src=Photos/slicer_selector.png
  >
</p>

* Create two slicers with one selecting the **"Table_Catalog"** and the other slicer selecting the **"Table_Schema"**

* You will **NOT** need to continuously run this code and will instead need this code to run and generate a new catalog table when there are updates inside of the GVR_PROD database

# Future Updates: 
* Config Code
* LBO
* PII or not PII
    * Personally identifiable information
* Dictionary Name (Business Name)
* Table Types
    * Type 1 or Type 2
* Incremental or Full Load
* Last load date

# Questions?

* You can contact me via email or GitHub!
    * Email: emilyporter920@gmail.com
    * GitHub Profile: Emily Porter || https://www.github.com/emilyporter920 
