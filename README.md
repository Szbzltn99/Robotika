# Robotika

https://www.tinkercad.com/things/aGxbcQC23aN-magnificent-wolt-hillar/editel?sharecode=jwXtv72TwRCqadYjSfziL8eVNKM3960OZnaDA8dOG9g


Kód:
void setup()
{
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(6, OUTPUT);
  pinMode(7, OUTPUT);
}

void loop()
{ //clockwise M1
  digitalWrite(4, HIGH);digitalWrite(5, LOW);
  delay(3000);
  //anticlockwise M1
  digitalWrite(4, LOW);digitalWrite(5, HIGH);
  delay(3000); 
  //stop M1 for 2 second 
  digitalWrite(4, LOW);digitalWrite(5, LOW);
  delay(3000); 
  
  //clockwise M2
  digitalWrite(7, HIGH);digitalWrite(6, LOW);
  delay(3000);
  //anticlockwise M1
  digitalWrite(7, LOW);digitalWrite(6, HIGH);
  delay(3000); 
  //stop M1 for 2 second 
  digitalWrite(7, LOW);digitalWrite(6, LOW);
  delay(3000); 
}
