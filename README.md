1. 
Assume the following list:   a = [66.25, 333, 333, 1, 1234.5] 
 
If you perform the following operations on the list: 
 
a.insert(2, -1) 
a.append(333) 
 
What will the list look like?  
66.25,333,-1,333,1,1234.5,333 
Text Box 
 
Now you perform:  
a.index(333) 
What will the output of this operation be? 
1 
Text Box 
 
 
a.remove(333) 
Text BoxWhat will the list look like? 
66.25,-1,333,1,1234.5,333 
 
 
a.reverse() 
 What will the list look like? 
333,1234.5,1,333,-1,66.25 
Text Box 
 
>>> a.sort() 
Text BoxWhat will the list look like? 
-1,1,66.25,333,333,123.5 
 
2. 
 
Write a short program to create a list of squares for numbers up to 10.  
Start with an empty list called squares and append squares of numbers from 0 up to 10. 
 
Print the contents of your list. 
 
squares = [] 
for x in range(0,10): 
    squares.append(x**2) 
print(squares) 
 
3. 
nums = [] 
for x in [1,2,3]: 
         for y in [3,1,4]: 
                if x != y: 
                        nums.append((x, y)) 
 nums 
 
What is the output from above?  
 
[(1, 3), (1, 4), (2, 3), (2, 1), (2, 4), (3, 1), (3, 4)] 
 
 
 
 
4. 
Create a program that will keep track of items for a shopping list.  
 
The program should start with an empty list and keep asking for new items until nothing is entered (no input followed by enter/return key).  
 
The program should then display the full shopping list. 
 
buy_list = [] 
x=0 
while x==0: 
    z=input("What do you want to buy ?") 
    buy_list.append(z) 
    if z=='': 
        print(buy_list) 
        break 
 
 
 
 
 
5. 
Write a program that will ask the user to enter two short sentences and then:  
 
Concatenate the two sentences into one long sentence  
Split the sentence into a list of words 
Sort the words in alphabetical order and print them out 
Print the total number of words contained in your list 
 
Create a dictionary that will store each word together with the count of the occurrence of each word in your sentence.  
   
Print each item from the dictionary 
 
x=input("Give me one sentences") y=input("Give me another sentences") print(x,y) z=x+" "+y split_z=z.split(' ') listofword=split_z print(listofword) sortlistofword=sorted(listofword) print(sortlistofword) print(len(listofword)) 

