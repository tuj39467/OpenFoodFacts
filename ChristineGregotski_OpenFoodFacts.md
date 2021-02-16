# OpenFoodFacts

## Project Abstract
Open Food Facts is an open source database dedicated to granting full access to nutritional facts for food items sold all around the world. Over 1.1 million products from 150 countries have been added by over 25,000 contributors by using the Android, iPhone, or Windows app, or their camera to scan barcodes and upload pictures of the product with their labels. Other users can edit previously uploaded food data to provide updates consistent with accuracy. Food data may include ingredients, allergens, nutrients, dietary labels, and much more. Every food item receives a NutriScore from A-E, A being the most healthy and E being the least healthy. Based on the provided data, users are able to compare products with certain brands to make healthier food choices.

![OpenFoodFacts](https://user-images.githubusercontent.com/70284962/108132845-8f2b3e00-7081-11eb-8077-2a8bc899aea2.png)

## Project Relevance
This project relates to the educational goals of Software Design (3296) because it includes the development of design patterns, issue tracking, version control, and debugging. Establishing design patterns is important in creating a model that assigns roles for each component of a program because the efficieny of a model impacts the accuracy of an overall program, so as to ensure that all parts of the program work without negatively affecting another. This may also affect the presentation of visuals and user accessibility to all of a program's features. Issue tracking is important in solving issues related to running a search of a specific product on the website because it is important to display accurate and relevant search results. This open source project is consistent in utilizing version control to organize different releases and attributes on Github, which is beneficial because it saves and reuses code to accommodate demands from different users. Debugging is a very useful process in understanding why certain errors occur in code and how to fix them, which is what this project achieves, but not in an optimal way since there are still errors.

## Conceptual Design
I wish to contribute to this project by fixing run-time errors such as "software errors" when trying to generate graphs representing food data. I would like to modify the design of the overall website because it seems dull and overwhelming by all of the compressed text, making it less user-friendly and confusing. I have noticed that the purpose of the website seems to be posted in all of the tabs, so I would suggest creating a separate "About" tab to locate this information. Furthermore, I believe that the "Discover" page should be the main page because it appears more straightforward in expressing the objective of the database, instead of having the user's first impression of the database to be just an average database. Otherwise, it seems redundant seeing the same text in the left column and bottom of the website. It resembles craigslist.com in how all of the images are displayed, which may give people a wrong impression of the purpose of the website. Overall, my main objective for designing this database is to make it appear minimalistic and simple. Additionally, monitoring what people upload is important because I found an unrelated post that was not food related, which can be the disadvantage of letting everyone edit and upload content. 

### Background 
https://github.com/openfoodfacts/openfoodfacts-androidapp.git


**Building**
- Fork the repository from the above link and clone it in Android Studio
- Follow the directions in Setup Guidelines under "Installation"

**Running**
- Configure the gradle to run in Kotlin
- Deploy APK from app bundle when configuring
- Run the main class

***Required Resources***
- Kotlin
- Java
- Android Studio
