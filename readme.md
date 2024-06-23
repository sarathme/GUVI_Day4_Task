# Note: Logic is same for all types of functions

### Question 1a (Print odd numbers in an array).

```
1 - Created a function called printOdd which accepts an array of numbers(arr).

2 - Loop through the array using for loop.

3 - Check each element in the array is not divisible by 2 if so log that number
in console.
```

---

### Question 1b (Convert all the strings to title caps in a string array).

```
1 - Created a function called titleCaps which accepts an string array(arr).

2 - Loop through the array(arr).

3 - Split each element using a space pattern(strArr).

4 - Check the if the length of the strArr is greater than 1 (i.e) the string has
two or more words.

4a - If step -4 is true, then loop through the strArr as it contains more than 1 word,

4b - Get the first letter (firstLet) using String substring method and covert to uppercase (toUpperCase method).

4c - Then concatinate the capitalized first letter with the remaining characters in the word.

4d - Repeat the same for each word in the strArr.

4e - Replace the converted string in the position.


5 - If Step 4 in false, then the string is a single word element, if so do the steps 4a, 4b and 4c.

6 - Replace the string in arr with its corresponding position.

```

### Question 1c (Sum of all numbers in an array).

```
1 - Created a function and assigned to a variable called sumArr accepting an array (arr) as a parameter.

2 - Initialize a variable sum as 0.

3 - Loop through the array and add each number in the array to the sum variable.

4 - Return the sum.


```

### Question 1d (Return all the prime numbers in an array).

```
1 - Created a function and assigned to the variable filterPrime accepting an array (arr) as a parameter.

2 - Initialized an variable res with an empty array.

3 - Loop through the array (arr), Initialize a variable isPrime with true.

3a - Find if each element in the array is divisible by any of its previous number using a for loop. If so set the isPrime variable to true and break out of the loop.

3b - If the previous loop ends the isPrime variable will be the indicator if an element in the array is prime or not.

3c - Check if the element is greater than 1 if so then check the isPrime variable if it is true then add the element to the res array.

4 - After the main loop return the res array.

```

### Question 1e (Return all the palindromes in an array).

```
1 - Created function and assigned it to  avariable palindrome.

2 - Initialize a variable (res) with an empty array.

3 - Loop through the array elements using for loop.

3a - Convert each element to a lowercased string and stored inside a variable (lower). Initialize a variable (reverse) as an empty string.

3b - Iterate through the string from the end using a forloop and concatinating each character in the reverse variable which gives the reversed value of the string.

3c - Check if the lower variable and the reverse variable are equal, if so add the array element to the res arr.

4 - Return the res variable which has the palindrome strings.

```

### Question 1f (Return median of two sorted arrays of the same size).

```
1 - Created a function and assigned it to avariable medianArr.

2 - Initialize a variable arr3 with an empty array and another variable k with 0.

3 - First for loop is for adding the elements of 1st array (arr1) to arr3 using k as the index of the element and incrementing it.

4 - The second for loop is to add the 2nd array (arr2) along with the already added arr1 elements to the arr3.

5 - Sorted the combined array (arr3).

6 - Find the 2 middle value index.

7 - Calculated the median and return the result.

```

### Question 1g (Remove duplicates from an array).

```
1 - Created a functiona and assigned it to a variable removeDuplicates.

2 - Initialized a variable with an empty array (res).

3 - Loop through the elements of the array.

3a - Check the index of each element in the res array using indexOf method if the element is not in the res array it returns -1.

3b - If it returns -1 then add that element to the res array. If not continue the loop.

4 - After the loop the res contains all the unique value of the given array.


```

### Question 1h (Rotate an array by k times).

#### Approach

1 - Rotating the last k elemnts in the array.

2 - Rotating the remaining elements in the array.

3 - Rotating the resultant array from the above steps.

4 - This function mutates the original array.

```
1 - Created a function and assigned it to a variable rotateArr which accepts two
parameters array (arr) and No. of times to be rotated (k).

2 - The
k = k % n (length of arr) is to reduce the number of rotation when k
is larger than the length of the array/

3 - The first for loop rotates the last
k elemnts in the array. by interchanging the elements k times using the k
variable 4 - The second for loop rotates the remaining elements in the array. 5
- The third for loop rotates the whole resultant array. 6 - After execution of
the loop the array will be rotated k times.
```
