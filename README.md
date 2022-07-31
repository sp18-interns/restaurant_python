# Restaurant Apps Description

## User app

- Login
- Logout
- Profile Management
- JWT based auth

## Ordering app

- Every order shall have a list of items in it with prices
- An item can be a recipe or a packed-item like cola, ice-cream, water-bottle, etc.
- If an item is a recipe, it should have a list of ingredients along with their quantities
- Order can have states - 
- Received, Accepted, Preparing, Prepared, In-Transit, Delivered, Canceled
- Once an order has been Prepared, the corresponding inventory should be updated
- Allow CRUD

## Recipe app

- Every edible/cookable item in the Menu should have a corresponding recipe to it.
- Recipe can have ingredients from inventory, cooking time
- DO NOT worry about the cooking steps. For now, add a list of steps and add random entries or an empty list for now. Even add the list of ingredients in the list of steps is fine for now

## Inventory app

- It keeps track of all the inventories in the restaurant - veggies, spices, fruits, non-edible items like tissues, tablecloths, cutlery, handwash, cleaning supplies, etc.
- For now, tie-up inventory with the ordering app. Everytime an order is Prepared, the inventory should update
- Inventory items can be listed in pagination, individual item details should be available for CRUD

## Billing app

- Every order will have a corresponding bill
- A bill shall have items along with their rate
- Items exist in the menu along with their rates
- Good to have - GST, Service tax on top of the cost total of items
- Allow CRUD
## Menu app
- Has a list of items with rates
- Each if type of item is recipe, then it should be tied with a list of ingredients
- Each item to have a corresponding rate
- Each recipe to be termed either vegetarian or non-vegetarian
