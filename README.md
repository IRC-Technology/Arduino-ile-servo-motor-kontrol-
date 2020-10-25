# Arduino-ile-servo-motor-kontrol-
/////////////////////////// IRC TECHNOLOGY /////////////////////////////  #include &lt;Servo.h> //Servo motorumuzun kütüphanesi  Servo sg90;  void setup() {   sg90.attach(10); //Servo motorumuzun data pini  }  void loop() {   sg90.write(180); //Servo motorun dönmesini istediğiniz açı  }
