# Loading in DataFrames from Files

##### 1. To load from the csv file

` df = pd.read_csv("pathfile.csv")`

##### 2. To load from the parquet file

` df = pd.read_parquet("pathfile.parquet")`

##### 3. To load from the excel file

` df = pd.read_excel("pathfile.xlsx")`
> Can also specify the specific sheets in excel file

` df = pd.read_excel("pathfile.xlsx", sheet_name="sheet1")`


### To change the file to another file formal use 

**.to_csv / .to_excel / .to_parquet**
