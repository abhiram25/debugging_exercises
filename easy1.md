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
   
4.  
   
