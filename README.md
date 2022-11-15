# pythonbasics
There is some python Programs which is i don in My College AI lab

1.Chatbot
a.using Dict-

dict={
        "hi":"Hello",
        "who are you ?":"I am chatbot",
        "what is your name ?":"My name is alexa"
}

a=input().lower()

if a in dict:
    print(dict[a])

Using List-

mylist = ["hi","Hello",
        "who are you ?","I am chatbot",
        "what is your name ?","My name is alexa"]

chat=input().lower()
if chat in mylist:
    if(mylist[0]==chat):
        print(mylist[1])
    elif(mylist[2]==chat):
        print(mylist[3])
    elif(mylist[4]==chat):
        print(mylist[5])
        
2.Area

a.Square

def areasq(side):
    area=side*side
    print(area)
side=int(input("Enter Side:"))
print("Area of Square:")
areasq(side)

b.triangle

def areatri(base,height):
    area=1/2*base*height
    print(area)
base=int(input("Enter base:"))
height=int(input("Enter height:"))
print("Area of triangle:")
areatri(base,height)

c.circle

def areacir(radius):
    pi=3.14
    area=pi*radius*radius
    print(area)
radius=int(input("Enter radius:"))
print("Area of circle:")
areacir(radius)
