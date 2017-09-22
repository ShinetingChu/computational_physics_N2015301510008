# The second work
* [Repoter](http://www.jianshu.com/writer#/notebooks/16425043/notes/17415529/preview)
* The original program
```
import turtle
import time

def name1(x,y,p,q):
    turtle.color("blue")
    turtle.pensize(5)
    turtle.speed(100)
    turtle.up()
    turtle.goto(x*p,y*q)
    turtle.down()
    turtle.seth(-0)
    turtle.forward(100)
    turtle.right(135)
    turtle.forward(141)    
    turtle.left(135)
    turtle.forward(100)
    
    
def name2(x,y,p,q):
    turtle.up()
    turtle.goto(x*p+150,y*q)
    turtle.down()
    turtle.seth(-45)
    turtle.forward(141)
    turtle.up()
    turtle.goto(x*p+250,y*q)
    turtle.down()
    turtle.seth(-135)
    turtle.forward(141)
    

def name3(x,y,p,q):
    turtle.up()
    turtle.goto(x*p+300,y*q)
    turtle.down()
    turtle.seth(-0)
    turtle.forward(80)
    turtle.right(90)
    turtle.forward(100)
    turtle.right(90)
    turtle.forward(80)
    turtle.right(90)    
    turtle.forward(100)
    turtle.up()
    turtle.goto(x*p+365,y*q-85)
    turtle.down()
    turtle.seth(-45)
    turtle.forward(35)
    
    
def main():
    turtle.setup(1366,768)
    p=70;q=30
    for x in range(-10,10):
        for y in range(-10,10):
            name1(x,y,p,q)
            name2(x,y,p,q)
            name3(x,y,p,q)
            time.sleep(0.1)
            turtle.clearscreen()

    
main()
```
* ![The result](https://github.com/ShinetingChu/computational_physics_N2015301510008/blob/master/The%20second%20work.PNG)
