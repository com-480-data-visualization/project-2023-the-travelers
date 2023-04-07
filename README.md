# Project of Data Visualization (COM-480)

| Student's name | SCIPER |
| -------------- | ------ |
| Chenyu Han| 331319|
| Haoying Lyu| 336582|
| Yuxin Wang| 338745|

### Brief Introduction
Our project aims to utilize data visualization techniques to present and compare important information about food, including its nutritional content, healthy diet combinations, and the differences in nutrition perspective of food production in different regions.

[Milestone 1](#milestone-1) • [Milestone 2](#milestone-2) • [Milestone 3](#milestone-3)

## Milestone 1 (23rd April, 5pm)

**10% of the final grade**

### Dataset
We decided to apply 4 main datasets, which will be presented below. 
1. [Food Ingredients] The dataset is a good starting point for analyzing nutrition data, as it contains columns with information on a range of nutrients such as energy, protein, fat, carbohydrates, fiber, sugar, calcium, iron, magnesium, phosphorus, potassium, sodium, zinc, and copper.
https://www.kaggle.com/datasets/thedevastator/now-with-more-nutrients
2. [FoodData Central - Nutrition and Component data] Provided by FoodData Central. It is a comprehensive collection of data on nutrients and other ingredients present in a wide range of foods and food products. It also provides a detailed and up-to-date view of their composition. 
https://www.kaggle.com/datasets/stoicstatic/fooddata-central-nutrition-and-component-data?select=lab_method.csv
3. [Diets, Recipes And Their Nutrients] This dataset contains a collection of recipes from various diets and cuisines that are designed to offer nutritious and healthy meal options.
https://www.kaggle.com/datasets/thedevastator/healthy-diet-recipes-a-comprehensive-dataset
4. [Nutrient Adequacy of Global Food Production] In this dataset, the nutrient sufficiency of the national food production was evaluated by combining data on food production from 191 countries and comparing it to the total quantity of nutrients that the population requires.
https://figshare.com/articles/dataset/Data_Sheet_1_Nutrient_Adequacy_of_Global_Food_Production_xlsx/17090456/1



### Problematic
**Overview**

 Diverse studies have revealed the importance of food on biological, cultural and psychological aspects. Biologically, food provides essential nutrients for development and maintenance of our bodies. Culturally, food plays a role in defining the identity of communities and cultures. Psychologically, food can have a significant impact on our moods and emotions. In this project, we hope to visually present and compare important information such as the nutritional content of food, so that users can enjoy the interface and interact with it to have healthier eating habits and understand the diverse connections between food and human civilization.

**Motivation & Target audience**


Food and quality nutrition are fundamental to human health and happiness, and even people's cultural identity.  Nutrients such as carbohydrates, proteins, fats, and vitamins are essential for many bodily functions, like energy production, tissue repair, immune function. Food cultures in different regions could influence people's daily lives and reflect their ways of thinking and emotional attitudes. Food can also be used as a coping mechanism to deal with stress and negative emotions. Eating certain foods can trigger the release of neurotransmitters. For instance, 5-hydroxytryptamine can affect our emotions.

Therefore, it is useful to know healthy food choices to help nourish our bodies and minds in a better way. Our motivation is to gain insight into various types of information about food, present it to users in a visual way, and provide them with healthier scientific choices about their diet. The target audience can be everyone, especially those who are interested in or concerned about eating healthy. In the immediate aftermath of the coronavirus outbreak, the quest for a healthy diet is even more passionate than ever. 

**Our goals**

Organize and compare food specific information to visualize the followings:
- Ranking of the levels of the main nutrients contained in the food that are required by the human body
- Comparison of the differences in the main food crops produced in different regions
- Evaluation and recommendation of healthy diet combinations



### Exploratory Data Analysis

Since we plan to use 4 different datasets, the preprocessing of each dataset is important before we combine them together. Here are some results of the preprocessings. Details can be found in the [notebook](https://github.com/com-480-data-visualization/project-2023-the-travelers/blob/master/Notebook/Milestone1.ipynb)
- Food Ingredients
    
    This dataset contains a list of food ingredients. We can obtain the distribution of food ingredients from this dataset.

- FoodData Central - Nutrition and Component data

    This dataset is relatively large, some of the csv files are compressed. To run the script correctly, please decompress them first!

    This dataset comes from U.S. Department of Agriculture, and contains several complex csv files. It contains some incorrect data, thus cleaning is necessary. 

    After basic processings, we can find some interesting and reasonable facts. For example, oil, butter and nuts are among the foods with highest energy, followed by popcorn, chocolate and chips. Companies like Hawaiian Host Inc., Lindt & Sprungli (Schweiz) AG and Alter Eco Americas Inc. are producing high-energy foods.

- Diets, Recipes And Their Nutrients

    This dataset contains nutrient values of different recipes. All of the recipes in this dataset belong to a certain type of diet (including dash, keto, mediterranean, paleo and vegan). After some basic processings, we can see the average nutrient values of different diets and different regions.

- Nutrient Adequacy of Global Food Production

    This dataset contains one excel file with 4 worksheets. It contains the food group contribution to different nutrients, and also adequacy ratio of different countries and nutrients. With basic processings, we can find out which countries produces different types of food products evenly, and which countries produces mainly one or a few types of food.

### Related work

During our search, we found many great data visualizations of food and were inspired by their work by:
- How should different foods be matched?

    The flavor of ingredients is provided by different chemicals, and combining ingredients with the same flavor often makes for delicious dishes. Researchers linked different ingredients with common compounds together with lines and compared them with existing recipes to form a complex network of relationships and found that Western chefs do tend to pair ingredients with common flavor compounds together. 
    https://www.scientificamerican.com/article/flavor-connection-taste-map-interactive/#

- The Rhythm of Food

    People's demand for different foods varies and is highly correlated with different seasons, dates and regions. This project compares Google search trends for hundreds of foods and visualizes them in terms of time changes, creating a unique "melody" of different foods. The project is an excellent example of data visualization with a clean color scheme and easily understood charts.
    https://rhythm-of-food.net/

- Fast food calories

    Even though people want to maintain healthy eating habits, they can't avoid the experience of eating fast food. So how to choose a suitable fast food restaurant. The authors calculated the calories of the food offered by different fast food restaurants and showed their distribution. The project makes a comparison between the traditional sense of non-healthy diet in a healthy and healthy direction.
    https://flowingdata.com/2016/12/12/calories-in-fast-food-menu-items/


## Milestone 2 (7th May, 5pm)

**10% of the final grade**


## Milestone 3 (4th June, 5pm)

**80% of the final grade**


## Late policy

- < 24h: 80% of the grade for the milestone
- < 48h: 70% of the grade for the milestone

