# Part 2 
1. It will print out 3 which is the length of prices as the input of discountPrice function. 
2. It will print out 150 as the discounted price for last item ($300) from prices list in the input. 
3. Similar to the last answer since finalPrice only store one value which it is the discounted price for last item (last i). So it will print out 150 again. 
4. It will return a vector of all price after applying the discount. As we all know that the function returns discounted (which is a vector) and it collects all discounted price. Therefore, in this example, we will get [50,100,150];
5. It will return an error since i is a let type and only can be accessed in the for loop scope. 
6. It will return an error because the discountedPrice is a let type and defined in the foor loop. Therefore, when we call it outside of for loop it will be an error. 
7. it will print out 150 which is the discounted price for last price. Since finalprice is not declared in the for loop, we can access it. 
8. It will print out the vector of all discounted price. Although we change all type to let, our return variable is still in the scope that we can use to access for every update. 
9.  It will return an error since i is a let type and only can be accessed in the for loop scope.
10. It will return 3 as the length of prices vector. There is no error becasue we didnt modify the const value again after the first assignment. 
11. The function will still return the vector of all discounted prices. Since there is no violation of data modification, the function will run properly. 
12. 
    1. ``` alert(student.name); ```
    2. ``` alert(student["Grad Year"]); ```
    3. ``` student.greeting(); ```
    4. ``` student["Favorite Teacher"].name;```
    5. ```student.courseLoad[0]; ```

13. 1. 32 Since we didn't convert the string before applying the addition. Therefore, it can only concatenates the string. 
    2. 1 We cannot perform '-' to a string, therefore, javascript converted 3 to a number. 
    3. 3 as an integer. Since 3 is an integer, null will convert to a 0.
    4. 3null This 3 is a string and null got converted to 'null' string.
    5. 4 the numeric value of true is 1. So we have 3 + 1.
    6. 0 Both numermic value of false and null is 0.
    7. 3undefined Since 3 is a string and undefined turned into a string.
    8. NaN Javascript turns both value to number due to the substraction and undefined 
14. 1. True It is a loose comparison which the number 2 is greater 1 . 
    2. False It is a string comparison which the 2 at first is larger than 1 at first. 
    3. True It is a loose comparision therefore both have the same value. 
    4. False It is a strict comparison and they dont have the same type. 
    5. False True is 1 in the numeric vule which is different from 2. 
    6. True Boolean(2) basically means true, therefore they are equal. 
15. == is for loop equality (tend to convert the data type of oprand into order to carry the comparison) and === is for strict equality (it doesn't do the type conversion and return false if the types are different). 
17. It will return a vector of double value from the original vector. The Modifyarray function takes in an array and the function double its parameter. Inside of Modifyarray, we run a for loop which take each value from array and apply it to the dosomehing and then return it in the newArray. 
19. 1 4 3 2 


