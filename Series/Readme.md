## Create A Series object from a Python List
```
pd.Series(list) 
```
<img width="440" alt="Screenshot 2022-03-16 at 3 21 35 PM" src="https://user-images.githubusercontent.com/98913678/158671909-c168f5fb-2c6b-4ba0-a1c9-b1cd32f0f62b.png">
<img width="255" alt="image" src="https://user-images.githubusercontent.com/98913678/158673045-f964223c-d9e2-41a0-8216-07f14a654259.png">

## Create A Series object from a Python Dictionary
<img width="285" alt="Screenshot 2022-03-16 at 3 25 36 PM" src="https://user-images.githubusercontent.com/98913678/158674003-8c655c7a-b11b-4561-a32f-4e7ec339774e.png">

## Series Object Attibutes
```<img width="647" alt="Screenshot 2022-03-16 at 3 45 22 PM" src="https://user-images.githubusercontent.com/98913678/158677061-aa3b92af-8d65-42ae-8807-ca76bfa8bde2.png">

Series.values
```
<img width="698" alt="Screenshot 2022-03-16 at 3 33 09 PM" src="https://user-images.githubusercontent.com/98913678/158675179-195c1bdd-30f4-4e52-9a3f-242339ba8f43.png">
```
Series.index
```
<img width="693" alt="Screenshot 2022-03-16 at 3 33 22 PM" src="https://user-images.githubusercontent.com/98913678/158675209-a8c1ed8a-9505-4efa-8ca1-ef50661f8680.png">

## Series Object Methods
```
Series.sum()
```
<img width="338" alt="Screenshot 2022-03-16 at 3 36 23 PM" src="https://user-images.githubusercontent.com/98913678/158675649-e83e3da6-0a53-4e96-8a96-c7b8c58af152.png">

```
Series.count()
```
<img width="329" alt="Screenshot 2022-03-16 at 3 36 58 PM" src="https://user-images.githubusercontent.com/98913678/158675745-44d7d300-45a7-4bf2-b98b-90c7ce009ce1.png">

```
Series.product()
```
<img width="321" alt="Screenshot 2022-03-16 at 3 37 31 PM" src="https://user-images.githubusercontent.com/98913678/158675851-50ac1193-3466-4b8b-a46e-819786fb4d11.png">

```
Series.mean()
```
<img width="326" alt="Screenshot 2022-03-16 at 3 37 58 PM" src="https://user-images.githubusercontent.com/98913678/158675934-029c78cf-5a58-4cad-9598-5db1301a41e4.png">

## Parameters and Arguments
<img width="652" alt="Screenshot 2022-03-16 at 3 46 08 PM" src="https://user-images.githubusercontent.com/98913678/158677157-2df29fd2-10aa-42fd-ae03-5dee5ec0fb3f.png">

```
pd.Seires(list_1, list_2)
```
<img width="657" alt="image" src="https://user-images.githubusercontent.com/98913678/158676946-1dcfabe0-c9c1-40b7-bc5f-544e5913f878.png">
<img width="474" alt="Screenshot 2022-03-16 at 3 47 19 PM" src="https://user-images.githubusercontent.com/98913678/158677362-3a637bfd-f783-4980-80eb-a55447ef57c6.png">

*What will happened when the number of two lists are not same?*

## Series with read.csv() Method
```
pd.read_csv('123.csv', usecols=["column1"])
```
<img width="538" alt="Screenshot 2022-03-16 at 3 51 05 PM" src="https://user-images.githubusercontent.com/98913678/158677923-607bb71e-0fbd-422f-8ca8-5e3741963fb4.png">

**Squeeze**
<img width="534" alt="image" src="https://user-images.githubusercontent.com/98913678/158679259-5785706f-9f00-4988-aa93-9138b1ba8e05.png">

## .head() & .tail()
<img width="275" alt="Screenshot 2022-03-16 at 3 58 35 PM" src="https://user-images.githubusercontent.com/98913678/158679495-eb85bce8-616b-4367-be17-848e8cc0b89f.png">

## .shape
<img width="248" alt="Screenshot 2022-03-16 at 4 03 44 PM" src="https://user-images.githubusercontent.com/98913678/158680408-1f0f438e-bb43-44e2-854a-16974a1ea35e.png">

## .sort_values() Method
<img width="460" alt="image" src="https://user-images.githubusercontent.com/98913678/158681252-f9296999-bd50-43b8-878d-11cea4461488.png">

Parameters: ascending=?

<img width="528" alt="Screenshot 2022-03-16 at 4 09 47 PM" src="https://user-images.githubusercontent.com/98913678/158681510-e45fcf76-dab8-47d2-ad06-7a5d99f7ee60.png">

.sort_values() wont change the original "google"

*How to change it permanently?*

<img width="570" alt="image" src="https://user-images.githubusercontent.com/98913678/158682586-fd77c3fb-745c-4a3a-aaa4-5f94a7efbfd8.png">

## .sort_index() Method

<img width="559" alt="Screenshot 2022-03-16 at 4 17 40 PM" src="https://user-images.githubusercontent.com/98913678/158683009-993aec31-93ff-4b12-bb14-062011438d59.png">

## Python in Method
```
 xxx in list
```

<img width="366" alt="Screenshot 2022-03-16 at 4 20 13 PM" src="https://user-images.githubusercontent.com/98913678/158683485-3d7497c1-fe9c-4b6d-b161-8c15c69614e1.png">

*Why????*


Because the **name** of the pokemon is the value.

<img width="405" alt="Screenshot 2022-03-16 at 4 21 45 PM" src="https://user-images.githubusercontent.com/98913678/158683783-08cb62ce-c97d-4638-a416-18df0269a2e7.png">


## Extract Values by Index Position
Just like how you get a item from a list in Python:

<img width="379" alt="Screenshot 2022-03-16 at 4 25 06 PM" src="https://user-images.githubusercontent.com/98913678/158684413-91706228-c563-41c4-8c80-64d92545cc3c.png">

**parameters: index_col**

<img width="770" alt="Screenshot 2022-03-16 at 4 32 15 PM" src="https://user-images.githubusercontent.com/98913678/158685623-7244b656-40f8-4bdf-8c7b-67357e13c6ce.png">

## .get() Method on a Series
**Parameter:**
<img width="674" alt="Screenshot 2022-03-16 at 4 36 37 PM" src="https://user-images.githubusercontent.com/98913678/158686233-9d0254cf-4ad0-49b5-b3aa-5659abdfbd2b.png">

<img width="419" alt="Screenshot 2022-03-16 at 4 34 51 PM" src="https://user-images.githubusercontent.com/98913678/158685986-aade531d-fdcb-4b12-938f-3bace6a7b37e.png">

## .idxmax() and .idxmin() Methods
```google.idxmax()```

<img width="279" alt="Screenshot 2022-03-16 at 4 40 15 PM" src="https://user-images.githubusercontent.com/98913678/158686801-50684e9c-7025-443b-af44-6122c03ed5a5.png">

<img width="301" alt="Screenshot 2022-03-16 at 4 40 50 PM" src="https://user-images.githubusercontent.com/98913678/158686913-6ccecb8e-9a70-4b8d-97fb-e5ee90d3fc7d.png">

## .value_counts() Method

```pokemon.value_counts()```

<img width="335" alt="Screenshot 2022-03-16 at 4 43 11 PM" src="https://user-images.githubusercontent.com/98913678/158687323-7333ec13-503c-45c7-bd0b-298a1e7ccd9c.png">

## .apply() Method
```
def classify_performance(number):
    if number < 300:
        return "OK"
    else:
        return "So Good"

```
.apply() method take a fucntion as a input, to apply it on **every single row**
<img width="490" alt="Screenshot 2022-03-16 at 4 47 53 PM" src="https://user-images.githubusercontent.com/98913678/158688176-e7324253-7d3b-44f9-bcd2-dc96cd54ce96.png">

**lambda**:

```.apply(lambda stock_price : stock_price + 1).head(6)```

<img width="641" alt="Screenshot 2022-03-16 at 4 51 35 PM" src="https://user-images.githubusercontent.com/98913678/158688756-ea2d8eae-af73-47b0-8f2c-2fa50ee64365.png">

## .map() Method

<img width="750" alt="Screenshot 2022-03-16 at 4 55 15 PM" src="https://user-images.githubusercontent.com/98913678/158689311-5ca52a82-baf6-4caf-b5ab-d9aa09c4760b.png">

.map() method used for *map* two data sets together

<img width="464" alt="Screenshot 2022-03-16 at 4 57 11 PM" src="https://user-images.githubusercontent.com/98913678/158689594-3a6134e3-7363-4486-bae8-146dbfdccb50.png">




