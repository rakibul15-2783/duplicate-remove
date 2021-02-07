# duplicate-remove
num=[2,3,2,4,5,6,6]
uniques=[]
for number in num:
    if number not in uniques:
        uniques.append(number)
print(uniques)
