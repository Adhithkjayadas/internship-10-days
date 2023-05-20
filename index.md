# 10 days internship

## Day 1

*Intalicized text*
**bold text**

> blockquote

1. open github.
2. create github acc
3. create a new file
4. change repository name of ("ilogic.c")

 	`code` code

--- Horizontal Rule 	

**bold**
```
#include<stdio.h>

main()
{
printf("hi");
}
```
[ADHITH K JAYADAS](https://github.com/Adhithkjayadas)

## PHOTO

![alt text](https://github.com/Adhithkjayadas/Test/blob/main/Screenshot_2023-05-11-10-56-49-220_com.miui.gallery.jpg)


# Day 2

- open tinkercad software
- open new simulation folder
- creat an a led simulation circuit without switch and with switch

### Led blinking without switch

![no loading](https://github.com/Adhithkjayadas/internship-10-days/blob/main/image/Screenshot%20from%202023-05-09%2012-14-35.png)

### Led blinking with switch

![no loading](https://github.com/Adhithkjayadas/internship-10-days/blob/main/image/Screenshot%20from%202023-05-09%2012-23-38.png)

# Day 3

- open tinkercad software
- open new simulation folder
- creat an a AND gate circute for op-amp using AND gate ic 7408

### And gate

![no loading](https://github.com/Adhithkjayadas/internship-10-days/blob/main/image/Screenshot%20from%202023-05-11%2010-43-12.png)

### Ardunino blink

![no loading](https://github.com/Adhithkjayadas/internship-10-days/blob/main/image/Screenshot%20from%202023-05-11%2011-13-21.png)

### Dencing led program

![no loading](https://github.com/Adhithkjayadas/internship-10-days/blob/main/image/Screenshot%20from%202023-05-11%2012-53-44.png)

# Day




# Day 4

### potentiometer using ardunio

![no loading](https://github.com/Adhithkjayadas/internship-10-days/blob/main/image/Screenshot%20from%202023-05-15%2014-28-51.png) 

## > program

const int potPin = A0;

void setup() {
  Serial.begin(9600); 
}

void loop() {
  int potvalue = analogRead(potPin);
    Serial .println(potvalue);
      delay(100);
}

# Day 5

### SEGMET COUNTER PROGRAM
![no loading](https://github.com/Adhithkjayadas/internship-10-days/blob/main/image/Screenshot%20from%202023-05-16%2009-12-37.png)

PROGRAM

``` 
void setup()
{
 

}

void loop()
  
{
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(6, OUTPUT);
  pinMode(7, OUTPUT);
  pinMode(8, OUTPUT);
  
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(2, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(8, LOW);
  delay(250);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(2, LOW);
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8, LOW);
  delay(250);
  digitalWrite(3, HIGH);
  digitalWrite(4, LOW);
  digitalWrite(2, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, LOW);
  digitalWrite(8, HIGH);
  delay(250);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(2, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8, HIGH);
  delay(250);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(2, LOW);
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(250);
  digitalWrite(3, LOW);
  digitalWrite(4, HIGH);
  digitalWrite(2, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, LOW);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(250);
  digitalWrite(3, LOW);
  digitalWrite(4, HIGH);
  digitalWrite(2, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(250);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(2, HIGH);
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(7, LOW);
  digitalWrite(8, LOW);
  delay(250);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(2, HIGH);
  digitalWrite(5, HIGH);
  digitalWrite(6, HIGH);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(250);
  digitalWrite(3, HIGH);
  digitalWrite(4, HIGH);
  digitalWrite(2, HIGH);
  digitalWrite(5, LOW);
  digitalWrite(6, LOW);
  digitalWrite(7, HIGH);
  digitalWrite(8, HIGH);
  delay(250);
 
 }
 

 ``` 
 # DAY-6

> introduction to AI & ML
1. Introduced a programming platform named as (Blockly) ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-12%2010-34-11.png)
2. The platform like Blockly are mostly used by  fresher's in programming
3. It's like a game 
4. The blockly helps to know about the programming easly
5. To create a multifunction program like a calculator ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-12%2012-21-17.png)
**AI & ML** 
> STM 32 NUCLEO DEVELOPMENT BOARD
 
![image](https://github.com/Adhithkjayadas/internship-10-days/blob/main/image/Untitled.jpeg)
1. the board is programmeble
2. Can program th board by nucleo software
3. it can build a sound detecting device by using microphone sensor 

# Day 7

# > Introducing drones by NAVANEETH 3rd year student of robotics

1. Introducing Drones
2. explained about drones parts
3. also speaked about the technical specifications like (Thrust,altitude,propeler diamention,weight management) 
4. To config the drones with software named as mission planner  ![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%202023-05-16%20at%2009-28-33%20mission%20planner%20-%20Google%20Search.png)
> Analog reader potentiometer
5. [tinker the circuit](https://www.tinkercad.com/things/dFZMDWtXe0k-pot-with-arduino/editel)
![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/Screenshot%20from%202023-05-15%2014-28-50.png)
2. related program shown in below

**program**
```
const int potpin=A0;

void setup() {
   Serial.begin(9600);
}
void loop() {
  int potValue =analogRead(potpin);
  Serial.println(potValue);
  delay(100);
}
```
# Day-8
 > Basics of 3D printing conducted by 3rd year student robotics
1. first introduced of the 3d printing
2. creating  models by the tinkercad 3D modeling
3. start with basic shapes
4. also cover the previous design's
5. created a base and top cover for the flower bottel by using [Tinkercad](https://www.tinkercad.com/)
6. then introduced the 3D printer 
7. also printed a design (duration 19 min)
8. 
# Day-9
> Introduced the yaskawa arm robot
1. The introduction of yaskawa AR1440 
![image](https://github.com/kpr22102210/10-Days-internship/blob/main/img/hhh.jpeg)
> Then introduced about the EV (electric vehicle)

# Day 10
> tokem display system
![image](https://github.com/Adhithkjayadas/internship-10-days/blob/main/image/Screenshot%20from%202023-05-20%2012-26-58.png)
> program
``` const int a = 2;
const int b = 3;
const int c = 4;
const int d = 5;
const int e = 6;
const int f = 8;
const int g = 7;
const int buttonPin = 10;   // pin to which button is connected

int counter = 0;
int buttonState = 0;
int prevButtonState = 0;
bool bPress = false;

void setup()
{
  pinMode(a, OUTPUT);
  pinMode(b, OUTPUT);
  pinMode(c, OUTPUT);
  pinMode(d, OUTPUT);
  pinMode(e, OUTPUT);
  pinMode(f, OUTPUT);
  pinMode(g, OUTPUT);
  
  pinMode(buttonPin, INPUT_PULLUP);
  display(counter);
  Serial.begin(9600);
  
}

void loop()
{
  buttonState = digitalRead(buttonPin); 
  if(buttonState != prevButtonState)
  {
    if(buttonState == 0)
    {
      bPress = true;
      counter++;
      if(counter > 9)
        counter = 0;
      Serial.print("Displaying ");
      Serial.println(counter);
      Serial.println();
      delay(100);
    }
    else
      Serial.println("Ready to accept button input");
    
    delay(200);
  }
  prevButtonState = buttonState;
  
  if(bPress)
  {
    shutdown();
    display(counter);
  } 
  
}

void display(int digit)
{
  if(digit!=1 && digit!=4)
    digitalWrite(a, HIGH);
  
  if(digit!=5 && digit!=6)
    digitalWrite(b, HIGH);
  
  if(digit!=2)
    digitalWrite(c, HIGH);
  
  if(digit!=1 && digit!=4 && digit!=7)
    digitalWrite(d, HIGH);
  
  if(digit!=1 && digit!=3 && digit!=4 && digit!=5 && digit!=7 && digit!=9)
    digitalWrite(e, HIGH);
  
  if(digit!=1 && digit!=2 && digit!=3 && digit!=7)
    digitalWrite(f, HIGH);
  
  if(digit!=0 && digit!=1 && digit!=7)
    digitalWrite(g, HIGH);
}

void shutdown()
{
  digitalWrite(a, LOW);
  digitalWrite(b, LOW);
  digitalWrite(c, LOW);
  digitalWrite(d, LOW);
  digitalWrite(e, LOW);
  digitalWrite(f, LOW);
  digitalWrite(g, LOW);  
} ``` 







