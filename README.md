# BLINK-button
Arduino project of Blink the LED from pin 13 written in c language with the function


HERE THE CODE


int a=13;
void setup()
{
  pinMode(a, OUTPUT);
}

void loop()
{
  blink(a);
}
void blink(int pin){
  digitalWrite(a, HIGH);
  delay(1000); 
  digitalWrite(a, LOW);
  delay(1000); 
  
}
