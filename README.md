# code 

/* 
  This program blinks LED connection to the pin number 13
*/  
int red = 12;

void setup()  
{  
  pinMode(red, OUTPUT);  
}  
void loop()  
{  
 // the first LED is made to blink one time  
  digitalWrite(red, HIGH);  
  delay(1000); // delay time in milliseconds  
  digitalWrite(red, LOW);  
  delay(1000);
}
