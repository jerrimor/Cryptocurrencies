# Cryptocurrencies

## Project Overview
Discover trends in crypto currency to show to the firm that this is the way to go for the future.  Unsupervised learning tools and methods are used for this project. KMeans was utilized by defining an elbow curve first to determine the number of clusters to use.  Then a 3D scatter graph was created to illustrate the different clusters. The data was initially cleaned and then filtered for a refined dataset to use.  The output was unknown, as is typical with unsupervised macine learning, so the model was used to group the cryptocurrencies. The analysis was completed so an accounting firm can evaluate the need and success of creating a new crypto currency class.  

## Summary
The cleaning and filtering brought the large dataset down, by removing null values and only analyzing currencies that are actively being mined. As mentioned previously, the KMeans algorigthm was used and the below elbow curve was created to show the inertia changing at k=4.

![03341E59-2FD9-479C-8E19-69B206AF7EC7_4_5005_c](https://user-images.githubusercontent.com/96222437/166131961-5fdf56ae-cde2-480c-aa94-681503cb85f5.jpeg)

The analysis shows there are 532 tradable cryptocurrencies that proves the success of this currency and how popular this type of currency is in the financial world. The classes were graphed in a 3D graph, as seen below.  And the final graph shared below is the scatter plot, created with hvplot to illustrate the coin supply vs the coins mined.  This gives a great picture to the demand and supply of the currency, and how a new class should find much success.  

![3B5898DE-BB88-44C2-BFB8-236DD7C9D60C](https://user-images.githubusercontent.com/96222437/166132044-747a04ba-0227-4482-aa12-480a495be4c9.jpeg)

![9D5FD705-1038-4F9F-8653-B76D4496FD48_4_5005_c](https://user-images.githubusercontent.com/96222437/166132024-78b3bd13-5ae6-4a4f-ab79-b85c45ff53f4.jpeg)
