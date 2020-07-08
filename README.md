# Pseudocode-the-Midterm


# Capitalize Sentences Function

~~~~ js

const capitalizeSentences = function(paragraph) {
  let result = '';

  for (let i = 0; i < paragraph.length; i++) {
    if (paragraph[i - 2] === '.' || i === 0) {
      result = result + paragraph[i].toUpperCase();
    } else {
      result = result + paragraph[i].toLowerCase();
    }
  }

  return result;
}

~~~~

1. Give function a name capitalizeSentences
~~~~ js

const capitalizeSentences = function 

~~~~
2. Make one parameter named paragraph
~~~~ js

const capitalizeSentences = function(paragraph)

~~~~
3. Name your final result and make it a string
~~~~ js

  let result = ''

~~~~
4. Create a forward loop starting at index 0, stopping at the parameter’s total length and incrementing once each time the loop runs
~~~~ js

  for (let i = 0; i < paragraph.length; i++) 

~~~~
5. If the paragraph at the current index of the loop down two spaces is equal to zero or the current index is equal to zero, 
~~~~ js

    if (paragraph[i - 2] === '.' || i === 0) 

~~~~
6. Then add the character in the paragraph at the index uppercased to the result
~~~~ js

      result = result + paragraph[i].toUpperCase();

~~~~
7. Otherwise, lowercase it
~~~~ js

else {
      result = result + paragraph[i].toLowerCase()

~~~~
8. Continue the loop
9. Return the final result of all the loops
~~~~ js

  return result

~~~~

# Check if Password is Valid Function

1. Give function a name isValidPassword
2. Make once parameter named password
3. If the password length is less than 12 characters 
4. Then its false 
5. Otherwise,
6. Create a forward loop starting at index 0, stopping at the parameter’s total length and incrementing once each time the loop runs
7. If the password has a space at the current index of the loop 
8. Then the result is false 
9. Continue the loop
10. Otherwise the result is true

# Make Half Squares Function 

1. Give function a name makeHalfSquares
2. Make one parameter named nums
3. Name your final result and make it an array
4. Create a forward loop starting at index 0, stopping at the parameter’s total length and incrementing once each time the loop runs
5. Multiply the number at the current index of the loop by itself and divide the result by two and add the results to the final array
8. Continue the loop
9. Return the final result of all the loops 

# Count Numbers over 90 Function 

1. Give function a name countAs
2. Make once parameter named nums
3. Name your final result and make it a number to add a count to 
4. Create a forward loop starting at index 0, stopping at the parameter’s total length and incrementing once each time the loop runs
5. If the number at the current index of the loop in the array is 90 or above
6. Add one to the result count
7. Otherwise, do nothing 
8. Continue the loop
9. Return the final result of all the loops 

# Delete Middle Letters

1. Give function a name deleteMiddleLetters
2. Make one parameter named str
3. Name your final result and make it a string
4. Make a number by rounding the parameter’s length divided by two and and name it middle
5. Create a forward loop starting at index 0, stopping at the parameter’s total length and incrementing once each time the loop runs
6. If the remainder of dividing two by the length of the parameter equals 1 and the value at the current index of the loop is not equal to the number middle or the the remainder of dividing two by the length of the parameter equals 0 and the value at the current index of the loop is not equal to the number middle and equal to middle down one space 
7. Then add the current character at the index to the result 
8. Continue the loop
9. Return the final result of all the loops 

# Hyphenate Name 

1. Give function a name hyphenateName
2. Make one parameter named name
3. Name your final result and make it a string
5. Create a forward loop starting at index 0, stopping at the parameter’s total length and incrementing once each time the loop runs
6. If the current index equals the last index of a space character in the name string
7. Then replace the space with a dash
8. Otherwise, add the character at the current index of the loop
8. Continue the loop
9. Return the final result of all the loops 
