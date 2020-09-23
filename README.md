# assignment2
q1)
a=int(input("enter 1stnumber"))
b=int(input("enter 2nd number"))
def calci(num,num2):
    if(a>b):
       print(a,"is greater",b ,"is smaller")
    else:
       print(b,"is greater and", a, "is samller")
 calci(a,b)
 
 q2)
 a=input("enter any data")
 b=list(a)
 for i,j in b,a:
 if (b[i]=="." or b[i]==","):
    b[i+1]=upper(j)
  print(a)

q3)
a=str(input("enter the data "))
b=list(a)
count=0
for i in a:
   if (i==" "):
     break:
    else:
       count+=1
       print(i)
       print(count+"word are there")
q4)
st=str(input(""enter the data"))
word1=input("enter which word you missed to write")
word2=input("enter which word you missed to write")
print("() is the one and only big()",format(word1,word2))

q5)
data types in python are two types:--
1)immutable datatype-- which doesn't change
2)mutable datatype---- which can change

immutable data type:--
    1)numbers--floart,integer ,long numbers comes under numbers data type
    2)strings--collection of characters is known as strings we can't do any modifications in this strings are enclosed with "","""""
    3)tuples--- tuples are also immutable we cant change data in tuples enclosed with () 
mutable data type:---
    1)lists--- lists are mutable we can change and enclosed with []
    2)dictionaries-- dictionaries are the collection of keys,and values
    3)sets--sets are also mutable but we enclosed it with {} adn duplicates not allowed

