# Python-for-Data-Science-AI-Development-
 pandas, numpy, statsmodel, matplotlib


Scenario: Shopping list

Task-1: Create an empty list  
At first, we need to create an empty list for storing the items to buy in the shopping list.

# Code
Shopping_list = []

Task-2: Now store the number of items to the shopping_list  
Items to add:  
- Watch  
- Laptop  
- Shoes  
- Pen  
- Clothes

# Code
Shopping_list = ["Watch", "Laptop", "Shoes", "Pen", "Clothes"]

Task-3: Add a new item to the shopping_list  
Seems like I missed one item "Football" to add to the shopping list.

# Code
Shopping_list.append("Football")

Task-4: Print the first item from the shopping_list  
Let's check the first item that we need to buy.

# Code
print(Shopping_list[0])

Task-5: Print the last item from the shopping_list  
Let's check the last item that we need to buy.

# Code
print(Shopping_list[-1])

Task-6: Print the entire Shopping List

# Code
print(Shopping_list)

Task-7: Print the items that are important to buy from the Shopping List  
Print "Laptop" and "Shoes".

# Code
print(Shopping_list[1], Shopping_list[2])

Task-8: Change the item from the shopping_list  
Instead of "Pen", I want to buy a "Notebook", let's change the item stored in the list.

# Code
Shopping_list[3] = "Notebook"

Task-9: Delete the item from the shopping_list that is not required  
Let's delete items that are unimportant; I don't want to buy Clothes, let's delete it.

# Code
Shopping_list.remove("Clothes")

Task-10: Print the shopping list  
We are ready with our shopping list.

# Code
print(Shopping_list)
