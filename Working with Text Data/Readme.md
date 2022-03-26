import pandas as pd
chicago = pd.read_csv("chicago.csv")
chicago.Department = chicago.Department.astype("category")
chicago.head(3)
## Common String Methods - .lower( ), .upper( ), .title( ) and .len( )
chicago = pd.read_csv("chicago.csv")
chicago.Department = chicago.Department.astype("category")
chicago.head(3)
chicago.Name.str.lower()
chicago.Name.str.title()
chicago["Position Title"] = chicago["Position Title"].str.title()
## The .str.replace( ) Method
chicago = pd.read_csv("chicago.csv").dropna(how="all")
chicago.Department = chicago.Department.astype("category")
chicago.tail(3)
chicago.Department.str.replace("MGMNT", "Management")
chicago.Department = chicago.Department.str.title()
chicago.head(3)
chicago["Employee Annual Salary"] = chicago["Employee Annual Salary"].str.replace("$", "").astype(float)
chicago["Employee Annual Salary"].mean()
## Filtering with String Methods
chicago = pd.read_csv("chicago.csv").dropna(how="all")
chicago.Department = chicago.Department.astype("category")
chicago.head(3)
mask = chicago["Position Title"].str.contains("water")
chicago[mask]
mask = chicago["Position Title"].str.startswith("water")
chicago[mask]
mask = chicago["Position Title"].str.endswith("ist")
chicago[mask]
## More String Methods - .strip( ), .lstrip( ), and .rstrip( )
chicago = pd.read_csv("chicago.csv").dropna(how="all")
chicago.Department = chicago.Department.astype("category")
chicago.head(3)
chicago.Name.str.strip()
## String Methods on Index and Columns
chicago = pd.read_csv("chicago.csv", index_col="Name").dropna(how="all")
chicago.Department = chicago.Department.astype("category")
chicago.head(3)
chicago.index = chicago.index.str.strip().str.title()
chicago.head(3)
chicago.columns=chicago.columns.str.upper()
chicago.head(3)
chicago = pd.read_csv("chicago.csv").dropna(how="all")
chicago.Department = chicago.Department.astype("category")
chicago.head(3)
chicago.Name.str.split(",")
chicago.Name.str.split(",").str.get(0)
chicago.Name.str.split(",").str.get(0).value_counts()
chicago["Position Title"].str.split(" ").str.get(0).str.title().value_counts()
chicago = pd.read_csv("chicago.csv").dropna(how="all")
chicago.Department = chicago.Department.astype("category")
chicago.head(3)

chicago.Name.str.split(",").str.get(1).str.strip().str.split(" ").str.get(0).value_counts()
## expand and n Parameters with .split( ) Methods
chicago = pd.read_csv("chicago.csv").dropna(how="all")
chicago.Department = chicago.Department.astype("category")
chicago.head(3)
chicago[["First Name", "Last name"]] = chicago.Name.str.split(",", expand=True)
chicago.head()
chicago[["First Title Word", "Last Title Word"]] = chicago["Position Title"].str.split(" ", expand=True, n=1)
chicago.head(3)

















