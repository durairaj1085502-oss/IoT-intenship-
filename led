# define pIRPIN 4
# define LED 3
# define IR 5
void setup() {
  // put your setup code here, to run once:
  pinMode(PIRPIN,INPUT);
  pinMode(LED,OUTPUT);
  pinMode(IR,INPUT);
}

void loop() {
  int l=digitalRead(PIRPIN);
  int i=digitalRead(IR);
  Serial.println("motion");
  Serial.println(l);
if(l==0&&i==1)
{
  digital.Write(LED,LOW);
}
else{
  digital.Write(LED,HIGH);
}
delay(1000)
}
