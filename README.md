# The Colored Bottles of Lurano

## Dataset description
An old town in a far away island, Lurano, had some artisans specialized in the making of fine glass bottles in different shapes and colors. We want to study the weight of those bottles and the features that influence their weight. 

But... you have access to a somehow limited information about those bottles, gathered by those who went to the island. You have a list of the properties of 10000 bottles, without their weight. You also have a list of the weight comparison for many pairs of those bottles. 

This weight comparison was done in a very rudimentary way. It says only if the first bottle of the pair is heavier or lighter than the second. If their weights are close enough (less than 0.1 kg of difference) the comparison is "undefined". 

And you have a small list of 20 bottles whose weight is known - these bottles are also present in the other files.

The known properties about those bottles are the name of their producer, their color and shape, their width, their height and their age (in months). Every property may (or may not) influence the weight of the bottle - even the color of the glass!

## Job done
1.	Obtain a good estimation for the weight of all those bottles. 
2.	Write a script in python that, when given a csv file like "bottles.csv", generate a csv file "bottles_with_weight.csv" that have a column with the weight estimation for each bottle based on their properties.

## File description
- Untitle.ipynb: Data Analysis and ML modeling
- bottles.csv: Train set
- bottles_with_weight_20: 20 known bottles weight
- comparisons.csv: list of the weight comparison for many pairs of those bottles
- train.csv: Dataset clean

## Interact with the project
Feel free to clone the repo and do your own analysis, If you find something interesting that I not mentionned, comment or feel free to contact me.

## Authors
Medhy Vinceslas

## License
Project under the CC0-1.0 License
