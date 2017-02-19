1. In the code below, we are getting an infinite loop, Figure out what the problem is and provide a solution to fix it so that the loop
   doesn't run infinitely.

   ```ruby
     loop do
       random_number = rand(10)
       break until random_number == 10
     end
   ```
