# NewliquidCrystal_ESP

Um die i2C Pins zu vergeben, muss im Setup Wire.begin(sdaPIN, sclPIN); ausgeführt werden, VOR lcd.begin();
Ansonsten werden die Standard Pins gesetzt, GPIO4, GPIO5.
