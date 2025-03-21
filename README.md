# data-types-in-python-
#checking data types of different value

a = 5
print("type of a: ", type(a))

b = 2.5
print("type of b: ", type(b))

c = "coding"
print("type of c: ", type(c))

d = True
print("type of d: ", type(a))

#new work
#making
name = 'khambani'
age = 57
is_student = False
weight = 180.7

#printing diffrent variables & there data types
print('Name: ', name)
print("Date type of name is ",type(name))

print('Age: ', age)
print("Date type of age is ",type(age))

print('Is_student: ', is_student)
print("Date type of name is ",type(is_student))

print('Weight: ', weight)
print("Date type of name is ",type(weight))

#Typecasting to change datatypes of variables
print("\n After Type Casting...")
age = str(age)
print(age)
print("Date type of age is ",type(age))
weight = int(weight)
print(weight)
print("Date type of weight is ",type(weight))

#new work
text = str(input("Enter a thing: "))

revtext = text[::-1]
text = revtext

print("Reverse of given thing is ")
print(text)
