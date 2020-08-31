# Blinking-led
In our very first experiment, we’re going to blink an LED on and off 
By using :

1 Breadboard ,
Arduino Uno R3 ,
1 LED , 
220Ω Resistor ,
2 Jumper Wires.

code - 


void setup()
{
  pinMode(10, OUTPUT);
}

void loop()
{
  digitalWrite(10, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(10, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
