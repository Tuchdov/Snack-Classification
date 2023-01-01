# Snack-Classification

The US Department of Agriculture maintains a rich dataset of food products and their detailed ingredients,
called FoodCentral Data or FDC. Each food product is branded, categorized and analyzed for the nutrients
it is made of. There are over 300K food products listed, divided to dozens of categories, of which over 70K
are snacks.
In our dataset there are ~35K snacks products (train and test combined), in 6 categories:
• Popcorn, Peanuts, Seeds & Related Snacks
• Candy
• Cookies & Biscuits
• Chips, Pretzels & Snacks
• Chocolate
• Cakes, Cupcakes, Snack Cakes
And the data contains 3 datasets:
1. food_train.csv and food_test.csv
2. nutrients.csv
3. food_nutrients.csv

The mission is to achieve the highest accuracy possible.

in this workflow I have split the date into 5 parts to handle: class_imbalance, feture engineering, feature
selection, model selection, and tuning to achieve the best performance
