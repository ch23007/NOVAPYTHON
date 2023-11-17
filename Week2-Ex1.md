#1.	Write a Python program that requests an integer
#value from the user. If the value is between 1 and 100
#inclusive, print ”OK” otherwise, print “Not OK”.


number = int(input("Please enter a number between 1....100: "))
if number > 0 and number <= 100:
   print("ok")
else: 
   print(number, "NOT OK")


SAMPLE TWO:
  
#number = input("Please enter a number between 1....100: "))
#if number > "0" and number <= "100":
#   print("ok")
#else: 
#   print(number, "NOT OK")
