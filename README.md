# string-concatenation-without-duplicates 
a=input()

b=input()

r=a+b

print(r)

print("".join(set(r)))

print("".join(sorted(set(r))))#prints in an order without duplicates

