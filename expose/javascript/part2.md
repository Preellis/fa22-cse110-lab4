1. It will log 3 to console since the var i is still in scope and its last value was 3.
2. It will log 150 to console as during the last loop dicountedPrice was set to 150 and it was declared using var so it is still in scope.
3. It will log 150 to console as that was the value of finalPrice in the last iteration of the for loop and finalPrice is in scope and not discarded since it was declared as var within the function.
4. It will return [50, 100, 150] since all the prices in the input array are halved when put into dicounted and the data refrenced by discounted is returned in the last line. There wont be any errors since all the variables are accessed within their scope.
5. i is no longer in scope when reaching line 12 since it was defined with let for the for loop block so the code will error.
6. discountedPrice is no longer in scope when reaching line 13 since it was defined with let inside the for loop block so the code will error.
7. It will log 150 to console as that was the value of finalPrice in the last iteration of the for loop and finalPrice is in scope since it was declared as let within the function (and not inside a nested block).
8. It will return [50, 100, 150] since all the prices in the input array are halved when put into dicounted and the data refrenced by discounted is returned in the last line. There wont be any errors since all the variables are accessed within their scope.
9. i is no longer in scope when reaching line 12 since it was defined with let for the for loop block so the code will error.
10. It will log 3 to console since length was assigned to the price array length in line 4.
11. It will return [50, 100, 150] since all the prices in the input array are halved when put into dicounted and the data refrenced by discounted is returned in the last line. Javascript arrays are stored by reference so there is no problem editing it with the push method even if defined as constant and the values of the discounted array will reflect the updates
12. 
    - A. `student.name`
    - B. `student['Grad Year']` 
    - C. `student.greeting()` 
    - D. `student['Favorite Teacher'].name` 
    - E. `student.courseLoad[0]`
13.
    - A. '32' since the 2 is cast to string and concatenated
    - B. 1 since the '3' is converted to number and subtraction then occurs
    - C. 3 since the null is cast to 0 and then added
    - D. '3null' since the null is cast to 'null' string then concatenated
    - E. 4 since the true is cast to 1 and added
    - F. 0 since both false and null are cast to numbers (0) and then aded
    - G. '3undefined' since the undefined is cast to 'undefined' and then concatenated
    - H. NaN since both are cast to numbers and the 'undefined' becomes NaN and subtracting by NaN results in NaN
14. 
    - A. true since '2' is cast to number and that is greater than 1.
    - B. false as they are lexographically compared and '2' comes lexographically after '12'
    - C. true as '2' is cast to number and it equals 2
    - D. false as the comparison is between things of different types which is false for ===
    - E. false as true is cast to number (1) and that is not equal to 2 
    - F. true as Boolean(2) is of the boolean type and is true since Boolean converts 2 to boolean true since 2 != 0
15. == is equlaity comparison after type casting. === is true only when values are of same type and equivalent.
16. see file
17. [2,4,6] will be returned since the callback function (which is doSomething) is executed on each element of the passed array before pushing to the newArr and doSomething returns 2 times the value inputed 
18. see file
19. 
        1
        4
        3
        2
    