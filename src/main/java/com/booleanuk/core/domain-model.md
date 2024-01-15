


## 1
``
As a member of the public,
So I can order a bagel before work,
I'd like to add a specific type of bagel to my basket.
``

Class Basket

| Class variables                          | Methods                        | Scenario                          | Output/Return          |
|------------------------------------------|--------------------------------|-----------------------------------|------------------------|
| Map<String, Map<String, Integer>> basket | addBagelToBasket(String bagel) | Add bagel from viable bagels      | correctly added bagel  |
| ArrayList<String> bagels                 |                                | which are listed in bagels list   | returns true and false |
| int capacityOfBasket                     |                                | Basket is constrained by capacity | if not                 |
|                                          |                                | made as a passed value            |                        |
|                                          |                                |                                   |                        |
|                                          |                                |                                   |                        |



## 2
``
As a member of the public,
So I can change my order,
I'd like to remove a bagel from my basket.
``

Class Basket

| Class variables                          | Methods               | Scenario                | Output/Return           |
|------------------------------------------|-----------------------|-------------------------|-------------------------|
| Map<String, Map<String, Integer>> basket | removeBagelFromBasket | Bagel gets removed from | True or false according |
|                                          |                       | basket.                 | to if bagel got removed |
|                                          |                       |                         | correctly               |
|                                          |                       |                         |                         |
|                                          |                       |                         |                         |


## 3
``
As a member of the public,
So that I can not overfill my small bagel basket
I'd like to know when my basket is full when I try adding an item beyond my basket capacity.
``

Class Basket

| Class variables                          | Methods               | Scenario               | Output/Return              |
|------------------------------------------|-----------------------|------------------------|----------------------------|
| Map<String, Map<String, Integer>> basket | checkIfCapacityIsFull | Checks if basket is at | True if bagel can be added |
| int capacityOfBasket                     |                       | max bagels             | false if not               |
|                                          |                       |                        |                            |
|                                          |                       |                        |                            |
|                                          |                       |                        |                            |


## 4
``
As a Bob's Bagels manager,
So that I can expand my business,
I’d like to change the capacity of baskets.
``

Class Basket

| Class variables      | Methods                              | Scenario                        | Output/Return             |
|----------------------|--------------------------------------|---------------------------------|---------------------------|
| int capacityOfBasket | changeCapacityOfBasket(int capacity) | Changes value of class variable | True if capacity got      |
|                      |                                      | capacityOfBasket                | correctly changed.        |
|                      | getCapacityOfBasket()                | Get the total capacity of bagel | Gets int capacityOfBasket |
|                      |                                      | basket                          |                           |
|                      |                                      |                                 |                           |


## 5
``
As a member of the public
So that I can maintain my sanity
I'd like to know if I try to remove an item that doesn't exist in my basket.
``

Class Basket

| Class variables                          | Methods                                  | Scenario                 | Output/Return |
|------------------------------------------|------------------------------------------|--------------------------|---------------|
| Map<String, Map<String, Integer>> basket | doesBasketContainBagel(String bagelName) | Check if basket contains | True if bagel |
|                                          |                                          | bagel according to name  | is in basket  |
|                                          |                                          |                          |               |
|                                          |                                          |                          |               |
|                                          |                                          |                          |               |
