```
week1=pd.read_csv("Restaurant - Week 1 Sales.csv")
week2=pd.read_csv("Restaurant - Week 2 Sales.csv")
customers=pd.read_csv("Restaurant - Customers.csv")
foods=pd.read_csv("Restaurant - Foods.csv")
```

## The pd.concat Method

sales = pd.concat(objs=[week1, week2], keys=["Week 1", "Week 2"])


<img width="295" alt="Screen Shot 2022-03-30 at 10 34 47 PM" src="https://user-images.githubusercontent.com/98913678/160964677-768ce19e-52e7-4e36-986c-a4990664bae5.png">

##### Using .loc to locate Customer ID

<img width="383" alt="Screen Shot 2022-03-30 at 10 35 00 PM" src="https://user-images.githubusercontent.com/98913678/160964698-84bb88c0-34d2-4081-a5f5-a07d7ac01a56.png">

## Inner .join

<img width="459" alt="Screen Shot 2022-03-30 at 10 35 37 PM" src="https://user-images.githubusercontent.com/98913678/160964771-9685802e-b380-494f-b2db-a0f5108130ba.png">

Find the same customer both from week 1 and week 2


<img width="701" alt="Screen Shot 2022-03-30 at 10 35 53 PM" src="https://user-images.githubusercontent.com/98913678/160964800-7b6db4ce-c5ef-4590-94dd-92f8a371aa19.png">

## Outer Joins

<img width="775" alt="image" src="https://user-images.githubusercontent.com/98913678/160964878-bde2cadd-71bc-43b1-99c0-6e6fd08e51c0.png">

## Left Joins

<img width="453" alt="image" src="https://user-images.githubusercontent.com/98913678/160964962-e4e92809-7524-4eac-9da4-fa0c2df380a4.png">


## The left_on and right_on Parameters

![image](https://user-images.githubusercontent.com/98913678/160965156-a5feaa41-e9a8-4cef-bfa3-43aebadd6f9d.png)

## Merging by Indexes with the left_index and right_index Parameters

![image](https://user-images.githubusercontent.com/98913678/160965362-306c0a45-7eaf-4338-ac80-c577dc222d71.png)

## .join( ) Method

![image](https://user-images.githubusercontent.com/98913678/160965556-1defd848-0a88-4edb-928c-bf63c8e2c9b7.png)

## The pd.merge( ) Method

![image](https://user-images.githubusercontent.com/98913678/160965618-c67d9b21-6366-468e-8167-efaa48cb5351.png)










