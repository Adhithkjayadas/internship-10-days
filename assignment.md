## tokem display system
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


