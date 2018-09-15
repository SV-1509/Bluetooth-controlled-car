char a='0';
void setup() {
  // put your setup code here, to run once:
  Serial.begin(38400);
  pinMode(10,OUTPUT);//enable right(er)
pinMode(11,OUTPUT);//enable left(el)
pinMode(2,OUTPUT);//right a(ra)
pinMode(3,OUTPUT);//right b(rb)
pinMode(4,OUTPUT);//left a(la)
pinMode(5,OUTPUT);//left b(lb)
}

void loop() {
  // put your main code here, to run repeatedly:
  if(Serial.available()>0)
  { 
     a=Serial.read();
     if(a=='F')//straight
{
digitalWrite(10,HIGH);
digitalWrite(11,HIGH);
digitalWrite(2,HIGH);
 digitalWrite(3,LOW);
 digitalWrite(4,HIGH);
 digitalWrite(5,LOW);
}
else if(a=='B')//Back
{
digitalWrite(10,HIGH);
digitalWrite(11,HIGH);
digitalWrite(3,HIGH);
 digitalWrite(2,LOW);
 digitalWrite(5,HIGH);
 digitalWrite(4,LOW);
}
if(a=='R')//Right
{
digitalWrite(10,HIGH);
digitalWrite(11,HIGH);
digitalWrite(3,LOW);
 digitalWrite(2,LOW);
 digitalWrite(4,HIGH);
 digitalWrite(5,LOW);
}
else if(a=='L')//left
{
digitalWrite(10,HIGH);
digitalWrite(11,HIGH);
digitalWrite(2,HIGH);
 digitalWrite(3,LOW);
 digitalWrite(5,LOW);
 digitalWrite(4,LOW);
}
if(a=='I')//FrontRight
{
analogWrite(10,150);
digitalWrite(11,HIGH);
digitalWrite(2,HIGH);
 digitalWrite(3,LOW);
 digitalWrite(4,HIGH);
 digitalWrite(5,LOW);
}
if(a=='G')//FrontLeft
{
analogWrite(11,150);
digitalWrite(10,HIGH);
digitalWrite(2,HIGH);
 digitalWrite(3,LOW);
 digitalWrite(4,HIGH);
 digitalWrite(5,LOW);
}
else if(a=='J')//BackRight
{
analogWrite(10,150);
digitalWrite(11,HIGH);
digitalWrite(3,HIGH);
 digitalWrite(2,LOW);
 digitalWrite(5,HIGH);
 digitalWrite(4,LOW);
}
else if(a=='H')//BackLeft
{
analogWrite(11,150);
digitalWrite(10,HIGH);
digitalWrite(3,HIGH);
 digitalWrite(2,LOW)=[[=;
 digitalWrite(5,HIGH);
 digitalWrite(4,LOW);
}
else if(a=='S')
{
  digitalWrite(10,LOW);
digitalWrite(11,LOW);
}
Serial.println(a);
}

a='0';
}
