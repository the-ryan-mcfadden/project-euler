#If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3,5,6, and 9. The sum of these multiple is 23. 
#Find the sum of all the multiples of 3 or 5 below 1000

multi_3_and_5 = []

for i in range(1000):
    if i % 3 == 0:
        multi_3_and_5.append(i)
    if i % 5 == 0:
        multi_3_and_5.append(i)

#the logic in this loops includes duplicates because numbers like 15 is a multiple of both 3 and 5.
#this creates a list of dictionary keys from the list. remember dictionary keys cannot be repeated. 
multi_3_and_5 = list(dict.fromkeys(multi_3_and_5))

print(sum(multi_3_and_5))
