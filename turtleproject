import turtle
dojo=turtle.Turtle()
dojo.color("orange","black")
cc=turtle.Screen()
cc.bgcolor("black")
#dojo.forward(100)
#dojo.left(40)
#dojo.fd(200)
dojo.speed(0)
#dont disturb now
def sign():
    dojo.begin_fill()
    dojo.fillcolor("orange")
    dojo.lt(180)
    dojo.circle(-150,180)
    dojo.right(90)
    dojo.fd(50)
    dojo.right(90)
    dojo.circle(100,180)
    dojo.right(90)
    dojo.forward(50)
    dojo.end_fill()

dojo.up()
dojo.goto(400,50)
dojo.down()
sign()
dojo.up()
dojo.goto(600,50)
dojo.left(90)
dojo.down()
sign()
#dont disturb cc 

def rectangle():
    dojo.forward(100)
    dojo.left(90)
    #dojo.fd(100)
    dojo.forward(100)
    dojo.left(90)  
    dojo.forward(100)
    dojo.left(90)
    dojo.forward(100)
def design1():
    #dojo.color("orange","black")
    dojo.up()
    dojo.goto(-600,-200)
    dojo.down()
    for i in range (1,100):
        rectangle()
        dojo.left(180%i)
def design2():
    dojo.fd(200)
    dojo.right(90)
    dojo.fd(150)
    dojo.right(90)
    dojo.fd(200)
    dojo.right(90)
    dojo.forward(150)
    dojo.left(50)
    dojo.fd(100)
    dojo.right(140)
    dojo.fd(200)
    dojo.right(40)
    dojo.fd(100)
     


#design1 deactivated

design1()
dojo.up()
dojo.goto(-500,100)
dojo.down()
design2()

def pattern():
    dojo.circle(100,extent=60)
    dojo.left(120)
    dojo.circle(100,extent=60)
    dojo.left(120)
def flower():
    dojo.begin_fill()
    no_OF_petals=10
    redius=100
    for i in range(10):
        pattern()
        dojo.left(360/10)
    dojo.fillcolor("orange")
    dojo.end_fill()

dojo.up()
dojo.goto(-200,-200)
dojo.down()

flower()
dojo.up()
dojo.goto(-200,0)
dojo.down()
flower()
dojo.up()
dojo.goto(-200,200)
dojo.down()
flower()
dojo.up()
dojo.goto(500,-100)
dojo.down()
for i in range(0,20):
    dojo.circle(100,1600)
    dojo.left(60)


dojo.hideturtle()


turtle.exitonclick()