1. In the code below, we are getting an infinite loop, Figure out what the problem is and provide a solution to fix it so that the loop
   doesn't run infinitely.

   Do not change the number after the `==` operator.

    ```ruby
      loop do
        random_number = rand(10)
        break if random_number == 10
      end
    ```

2.  On line 7, when word is printed, the output is `nil` instead of printing "great".

    What is the problem?

    What is the solution?


    ```ruby
      def remove_white_space(str)
        str.rstrip!
      end

      word = remove_white_space("Great")

      puts word
    ```

    What is the problem?

    Put your solution here.

3. We want to check if a single lowercase letter is covered within the `("a".."z")` range.

   If multiple letters are added as an argument, we want it to return false.

   Identify the problem and modify the code to where the first line of code evalutes to true
   and the second line of code evaluates to false.

   DO NOT change the arguments in the parameters or the range.


   ```ruby
      ("a".."z").cover?("z") => true
      ("a".."z").cover?("ef") => true
   ```

4.  We want to create a program that outputs every number from 1 to 10 inclusive, but only if the number is even. So we write the following program:

  ```ruby
    array = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
    counter = 0

    loop do
      number = array[counter]

      if number.even?
        puts number
      else
        counter += 1
      end
      break if counter >= array.length
    end
  ```

  Run the code and see if it outputs what we want it to. If it doesn't, what is the problem and how do we fix it?

5. After looking at the last problem, we decide to make our code a little more succinct, so we refactor it to this:

  ```ruby
    (1...10).each do |number|
      puts number if number.even?
    end
  ```

  Does this achieve the results we want specified in question 4? Why or why not?
  
6. 
