# assign1
i= []
for n in range(2000,3201):
    if n%7==0 and n%5 !=0:
         i.append(n)
print(i)


first_name= input('enter first name:')
last_name = input('enter last name: ')
print(last_name , first_name)


d = int(input('enter the diameter:'))
r = d/2
PI =3.14

v=4/3 *PI*r**3
v
