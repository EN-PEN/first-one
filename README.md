void setup() {
  // put your setup code here, to run once:
pinMode (3,OUTPUT);(設定輸出腳)(INPUT = 11不亮)(OUTOUT = 01亮)
}

void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(3,LOW); (低電位)
delay(100);(時間)
digitalWrite(3,HIGH);(高電位)
delay(100);(時間)
}
