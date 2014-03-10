iconclock
=========

Arduino clock with icon alarm display on an LCD12864 graphical LCD

This is the code for an Arduino-based alarm clock that flashes a graphical
representation of the reason for the alarm on its LCD display.  The hardware
consists of:

  o Arduino Uno
  
  o LCD12864 GLCD (w/ST7920 controller) sheild with joystick on analog input A0
      http://www.dfrobot.com/index.php?route=product/product&product_id=1084

  o DS1307 battery-backed real-time clock chip
      http://www.dfrobot.com/index.php?route=product/product&product_id=879
      http://www.adafruit.com/products/264
      
  o Piezo buzzer (type CEM-1203)
      http://www.adafruit.com/products/1536
      https://www.sparkfun.com/products/7950
      
The code reads the DS1307, displays the time, allows the user to change the time,
add alarm events, select pre-compiled icons to attach to alarm events, and alert
the user with beeping and a graphical image when the alarms trigger.


      
