# The container Port

A ship can carry metal, water and wheat. For that it has three compartments.
The ship's capacity is 100 tons of metal, 46 tons of water and 73 tons of wheat.


To be filled up, it needs to first load metal then water then wheat (otherwise the ship is unbalanced and could sink)
For that, it first stops at the metal loading dock, then goes to the water loading dock and finally to the wheat loading dock. Then if there is still room, it starts from the beginning again until the amount left to be loaded is less or equal to the average delivery quantity of the loading dock. So if the average quantity of the metal loading dock is 15 tons, then the ship will try to load until it has at least 85 tons of metal.


The loading docks are not very intelligent and do not always deliver the same quantity.
For the metal dock, the minimum quantity is 12 tons and the maximum quantity is 18 tons (average 15)
For the water dock, the minimum quantity is 3 tons and the maximum quantity is 4.8 tons. The water is only delivered in .2 units (so 3,3.2,3.4 but not 3.1 or 4.7)
For the wheat dock, the minimum quantity is 12 packs and the maximum quantity is 16 packs. A Pack weights 3.4 tons

## To-Dos:

- Understand the problem, read it until it is clear what happens
Hint: Make a drawing that illustrates the problem so that you can see what is happening


- Write a function that simulates the metal dock
- Write a function that simulates the water dock
- Write a function that simulates the wheat dock


- Write a function that simulates one round. Going to each dock and loading. The program should display "Loaded x metal, y water and z wheat"
- Write a function that loads the boat