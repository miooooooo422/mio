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

Whad did we learn?
We learned basic commands in Python. We leaned differnt functions such as draw, fill, and text and practiced by adding color to the circles or changing their sizes.

Questions?
Nothing

Homework for next class
1 Add lines from the middle of the window to each circle
2 Add lines from circle to circle


what did we learn

How to make a circut

Questions 
no

HW idk

we created:

void setup()
{
  pinMode(13, OUTPUT);
    pinMode(12, OUTPUT);
      pinMode(11, OUTPUT);
  		pinMode(10, OUTPUT);
    		pinMode(9, OUTPUT);
  				pinMode(8, OUTPUT);
  					

}

void loop()
{
  digitalWrite(13, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(13, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(12, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(12, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(11, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(11	, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(10, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(10, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(9, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(9, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(8, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(8, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  
}




