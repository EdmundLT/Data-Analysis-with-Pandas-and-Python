## Dataframe Basic

<img width="783" alt="Screenshot 2022-03-17 at 9 40 18 PM" src="https://user-images.githubusercontent.com/98913678/158921158-b675a351-1782-43f1-94b8-6f3ba1bcfe5c.png">

## basic method

1. .index
2. .values
3. .shape
4. .dtypes
5. .columns
6. .axes
7. .info()


<img width="728" alt="Screenshot 2022-03-17 at 9 40 56 PM" src="https://user-images.githubusercontent.com/98913678/158921217-28afc979-7846-47ca-8ce5-2f052bc13cfd.png">

## .sum()

<img width="589" alt="Screenshot 2022-03-17 at 9 42 14 PM" src="https://user-images.githubusercontent.com/98913678/158921347-c68637a4-d8a1-4753-9d1f-d0f6727bd0ca.png">

## How to call a column

```.column_name or ["column_name]```

<img width="1113" alt="Screenshot 2022-03-17 at 9 42 39 PM" src="https://user-images.githubusercontent.com/98913678/158921401-2e22c692-1d5d-4ada-a6e0-bedaf22ef7bb.png">

## Select Two or More Columns

<img width="435" alt="Screenshot 2022-03-17 at 9 43 27 PM" src="https://user-images.githubusercontent.com/98913678/158921459-71b03872-4a64-4fe6-83da-b488921687aa.png">

## Add new Column to Dataframe

<img width="865" alt="Screenshot 2022-03-17 at 9 43 44 PM" src="https://user-images.githubusercontent.com/98913678/158921481-b3bdefa4-11cb-4250-a0e3-a849b30466de.png">

## .insert() Method
```nba.insert(3, column = "Gender", value = "Male")```

<img width="941" alt="Screenshot 2022-03-17 at 9 44 12 PM" src="https://user-images.githubusercontent.com/98913678/158921519-3db07ef6-c85b-4c9c-82d3-0faa8f3a2d96.png">

## Broadcasting Operations

<img width="945" alt="Screenshot 2022-03-17 at 9 45 10 PM" src="https://user-images.githubusercontent.com/98913678/158921613-70121a6f-5607-4064-830a-aa543a055a8f.png">

## A review of the .value_counts() Method

<img width="468" alt="Screenshot 2022-03-17 at 9 45 29 PM" src="https://user-images.githubusercontent.com/98913678/158921640-d4cfd271-8516-4e61-a3f5-43bf0fc80fa5.png">

## Drop Rows with Null Values

```dropna.()```

<img width="749" alt="image" src="https://user-images.githubusercontent.com/98913678/158921864-047e5a67-c204-45e1-b88f-1c216bb0cab3.png">

**Parameters: how=?**

<img width="753" alt="image" src="https://user-images.githubusercontent.com/98913678/158922124-bb5646f6-7859-4067-b1be-a0e6cecbcb5a.png">

## Fill in Null Values with the .fillna() Method

<img width="749" alt="image" src="https://user-images.githubusercontent.com/98913678/158922362-a8a54028-6324-4810-8156-450ac7fa355f.png">

<img width="746" alt="image" src="https://user-images.githubusercontent.com/98913678/158922458-65dd50dd-0cfd-4e1d-9052-b70141dec078.png">

## The .astype() Method

.astype( ) is a method to change the datatype of columns

<img width="698" alt="image" src="https://user-images.githubusercontent.com/98913678/158922702-b4008f47-4708-4d96-aa4a-970de271b9dc.png">

<img width="461" alt="Screenshot 2022-03-17 at 9 56 28 PM" src="https://user-images.githubusercontent.com/98913678/158922735-ba6693a8-4ca6-43b0-a82c-37e491fc7911.png">

**New Datatype: Category**

When we use category type? 

<img width="482" alt="image" src="https://user-images.githubusercontent.com/98913678/158922819-924605f8-267c-4316-a4ca-993afa59ac7a.png">

As you can see, column "Position" are [PG, SG, SF, PF, C], why we dont combine it together?

<img width="588" alt="image" src="https://user-images.githubusercontent.com/98913678/158922979-46e8fd97-49e7-43cf-b9f7-d0a60847345f.png">

**After we combined it together, the memory usage decreased around 20%!**

## Sort a dataframe with .sort_values() Method

if we set ```na_position``` = first, the NaN Value of College will put on the top of Dataframe

<img width="802" alt="Screenshot 2022-03-17 at 10 00 33 PM" src="https://user-images.githubusercontent.com/98913678/158923099-669ccdc7-2e5a-4f2a-bcd3-0f60c7295417.png">

**How we sort multiple columns?**

<img width="807" alt="image" src="https://user-images.githubusercontent.com/98913678/158923620-81255687-94ac-4b98-88ee-4796669b31fa.png">

## Sort DataFrame with .sort_index() Method

<img width="767" alt="image" src="https://user-images.githubusercontent.com/98913678/158923745-c2e7f6ec-33ba-40c1-8d79-c242b9e6cb78.png">

## Rank Values with the .rank( ) Method

<img width="819" alt="image" src="https://user-images.githubusercontent.com/98913678/158923927-5b5cf9c1-00a8-4644-a284-e2f16b8367af.png">




<img width="802" alt="Screenshot 2022-03-17 at 10 00 33 PM" src="https://user-images.githubusercontent.com/98913678/158923099-669ccdc7-2e5a-4f2a-bcd3-0f60c7295417.png">

<img width="888" alt="image" src="https://user-images.githubusercontent.com/98913678/158924035-22e5b331-133b-4514-92f5-ac8b82059383.png">


