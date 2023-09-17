
 #  Program for prime number
     
     def number (n)
     count = 0
      
       
       if (n == 2 || n == 3 )
            count=0

       elsif(n==1)
           count += 1
         
     elsif (n % 2 == 0 || n % 3 == 0)
            count +=1
       
     end
 
          if (count == 1)
              puts "#{n} is not prime number"
          else 
            puts "#{n} is prime number"
          end
     end

number (11629)
