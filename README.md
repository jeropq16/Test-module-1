Readme for the test module one

In this readme, I will explain with examples how the program I developed for the test of module one.


The first thing they asked us was to have 5 initial products

In all data entries a method called .replace was used to allow the user to enter or separate the words by spacing, since if the method is not used, they enter a space and the program takes it as an invalid character            

Then a function was created that allows us to add products with price and quantity, in case a value that does not correspond is entered, the program shows a message and again asks for the value until an allowed value is entered

if we use the function of searching for products, the program will ask for the name of the product to look for it in the dictionary, if it finds it shows it with price and quantity; in case it does not find it will show a message that the product does not exist in the inventory

we continue with the option of updating price and updating quantity, in both the same methods of verification of invalid tickets are used. the user is asked for a name, prompted to enter the new price or quantity, and the new price is saved in the dictionary


Delete products function:
For the function of deleting products, the del was used that is going to enter the dictionary and with the name that the user entered, the del is going to remove it from the dictionary

The function of showing inventory all it does is take key and value of each product from the dictionary and show them

Total inventory function:
What this function does is that lambda takes each price from the dictionary and multiplies it by each quantity, adds it all up and the user only sees the total value of the entire inventory

Finally there is the main menu, this is in a while true loop with the 8 options of the program, until you enter a valid one, it will be an infinite loop. when a valid option is entered, the program directly takes you to the function you want to use

INPUT AND EXIT CASES

Example of function add products


![imagen](https://github.com/user-attachments/assets/21d017f6-c3e8-4b45-8dc2-5611449b0595)


![imagen](https://github.com/user-attachments/assets/cdf2d4b1-5658-4f1f-86ca-f143a662cbfd)











