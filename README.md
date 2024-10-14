پروژه رسم sin و cos هم زمان
void setup() {
  // put your setup code here, to run once:
Serial.begin(9600);
}

void loop() {
  // put your main code here, to run repeatedly:
for(float t = 0 ; t < 360 ; t++)
{
  float rad = (sin(t*PI/180));
  Serial.print(rad);
  delay(1);
  
  Serial.print("     ");

  float rad1 = (sin(t*PI/180));
  Serial.print(rad1);
  delay(1);
}
}
رسم این پروژه را میتوان در serial plotter مشاهده کرد
