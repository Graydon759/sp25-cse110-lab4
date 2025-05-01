1. It will print "3". This is because i will iterate until the length of prices which is 3. Since i is a var this val will stay stored in i.
2. It will print "150". This is because DiscountPrice is a var so it will store the last value it was set to and the last value of DiscountPrice is 150.
3. This will also print "150". This is because finalPrice is a var and the last val stored in finalPrice was 150.
4. The function will return the array [50, 100, 150]. The function will return the correct answer this time but may not in future calls. This is because many of the variables declared in the function should not be var because of the problems of using vars (aka them being similar to global variables).
5. Since i is not defined in the scope where as the line 12 is called the output there will be an error.
6. Since discountedPrice is not defined in the scope where as the line 13 is called the output there will be an error.
7. It will print out 150 since finalPrice is declared as 0 earlier in the same scope as line 14. Then in the for loop finalPrice is changed. The final value of finalPrice is 150 after all the changes.
8. The function will return the array [50, 100, 150]. However, unliked the function in Questions 1-4 this function will act correctly uppon repeated use. This is because the variables are defined with let instead of var.
9. The code would result in an error. This is because i isn't defined in the same scope as 11.
10. The code would print "3". This is because length is set as 3 in line 4.
11. It would return the array [50, 100, 150] since you can push onto a const array. This function would also work correctly when called multiple times.
12a. student.name
12b. student['Grad Year']
12c. student.greeeting()
12d. student['Favorite Teacher']
12e. student.courseLoad[0]
13a. 32 converts 2 to a string
13b. 1 converts 3 to an num
13c. 3 converts null to 0
13d. 3null convers null to a string
13e. 4 converts true to 1
13f. 0 converts both null and false to 0
13g. 3undefined undefined to converted to a string
13h. NaN since undefined cant be converted to a num
14a. true converts '2' to a num
14b. false converts '2' and '12' to nums
14c. true converts '2' to a num
14d. false since they arent exactly the same
14e. false converts true to 1
14f. true Boolean(2) = true and true === true
15. == compares after converting each side to the same type but === compares without converting each side to the same type
17. The result will be an array of [2, 4, 6]. The function modifyArray creates a empty array. Then it has a for loop that goes through the array that is passed in. The array that is passed in is [1, 2, 3]. For each element in the original array it is passed into the function that is passed into modifyArray (via the callback variable). This new value that is calculated is put into the empty array. Then the function modifyArray returns the new array.
19. It will print:
    1
    4
    3
    2