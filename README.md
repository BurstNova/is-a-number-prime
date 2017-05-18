# is-this-number-prime?
#This is a program I coded that checks to see if a number is a prime number.

def isPrime(num)
  num >= 2 ? (2..num-1).all?{|n| num % n != 0} : false
end
