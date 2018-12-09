//Sketch_nov25_LCDtest

#include <LiquidCrystal.h>

LiquidCrystal lcd(12, 11, 5, 4, 3, 2);

void setup() {
  lcd.begin(16, 2);
  lcd.print("Hello --- Sarah --- Maria + Nynka!");
}

void loop() {
// lcd.cursor();
// delay(500);
// lcd.noCursor();
// delay(500);

lcd.setCursor(0, 0);
lcd.cursor();
delay(400);
//lcd.setCursor(12, 1);
//lcd.noCursor();
//delay(500);
//lcd.noDisplay();
//delay(500);

lcd.scrollDisplayLeft();
//delay(200);
}

// delay(500);

 // lcd.display();

