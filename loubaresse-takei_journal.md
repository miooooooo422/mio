#This is my journal

What did we do?
We worked on processing:

we created:
```.py
def setup():
    size(1000,1000)
    background(255)
    textAlign(CENTER)

def draw():
    print("")
    
def mouseClicked():
    x = mouseX
    y = mouseY
    z = random(0,200)
    myred = random (0,255)
    myblue = random (0,255)
    mygreen = random (0,255)
    fill(myred, mygreen, myblue)
    
    circle(x, y, z)
    fill(0)
    textSize(z/3)
    text ("M",x,y)


```

Whad did we lean?
Basic commands

Questions?
Nothing
