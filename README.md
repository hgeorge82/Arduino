# Arduino
### LED blink revisited code
void setup() {
  // set up serial moniter
  Serial.begin(9600);
  pinMode(13, OUTPUT);
  Serial.println("Hello Hope");
}

void loop() {
  Serial.println("Hello Hope");
  delay(1000);

  digitalWrite(13, HIGH);
  Serial.println("Hello Hope");
  delay(100);
  digitalWrite(13, LOW);
  Serial.println("Hello Hope");
  delay(100);
}
### Evidence
<img src="Videos/IMG-1909.mov" width="200">
