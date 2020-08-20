
## Verkefni 3 (10%)
Búðu til í Github Repository vefsíðu (Verkefni 3) í Wiki sem inniheldur eftirfarandi fyrir liði; 3.1, 3.2:

* svör við spurningum.
* tengla á 3D Tinkercad lausnir.
* tengla á myndbönd af verklegum verkefnum.
* tengla á kóðaskrár sem þú notar í verklegum verkefnum.

### 3.2 DC motor og Transistors (5%)

1. Kynntu þér eftirfarandi [Motors and Motion](https://www.instructables.com/lesson/Motors-and-Motion/)
og [Transistors](https://www.instructables.com/lesson/Transistors/) og svaraðu eftirfarandi spurningum:

   1. Hvernig er skrefmótor (e. stepper motor) ólíkur hefðbundnum DC mótor? 
   1. Hvernig er stýrimótor (e. servo motor) ólíkur hefðbundnum DC mótor? 
   1. Hvernig er hægt að stjórna í hvora áttina DC mótor snýst?    
   1. Hvað gerir transistor?
   1. Hver er munurinn á NPN og PNP transistorum?

1. Fylgdu [Lesson 13. DC Motors](https://learn.adafruit.com/adafruit-arduino-lesson-13-dc-motors) og settu hann upp í TinkerCad.

1. Svaraðu eftirfarandi spurningum:

   1. Afhverju þurfum við að nota PWM pinna til að stýra DC mótor?
   1. Afhverju þurfum við að nota viðnám, transistor og diode með DC mótor í _Lesson 13. DC Motors_?

1. Fylgdu [Lesson 13. DC Motors](https://learn.adafruit.com/adafruit-arduino-lesson-13-dc-motors) verklega með brauðbretti, DC motor og íhlutum.



### 3.3 DC motor og H-Bridge (5%)

1. Fylgdu [Lesson 15. DC Motor Reversing](https://learn.adafruit.com/adafruit-arduino-lesson-15-dc-motor-reversing) og settu hann upp í:
   1. TinkerCad
   1. Verklega

1. Lestu þér til um [L293D H-Bridge](https://maker.pro/custom/projects/all-you-need-to-know-about-l293d) og svaraðu eftirfarandi spurningum:

   1. Hvað er hægt að gera með L293D?
   1. Hver er munurinn á L293 or L293D?
   1. Í lesson 15 er eftirfarandi kóðabútur, útskýrðu hann útfrá H-Bridge
   ```
   void setMotor(int speed, boolean reverse)
   {
     analogWrite(enablePin, speed);
     digitalWrite(in1Pin, ! reverse);
     digitalWrite(in2Pin, reverse);
   }
   ```
   1. L293D er með tvo +V pinna (8 and 16), útskýrðu þá.
  
1. Lestu þér til um [mismunandi tegundir mótora](https://learn.adafruit.com/adafruit-motor-selection-guide/types-of-motors) og horfðu á þessi [tvö myndbönd](https://www.youtube.com/playlist?list=PLRIGIzu0Z7KlYY6FyZ0_Y0ZmVFyAvtDO0). <br>
Nefndu i hvaða tilfellum (komdu með dæmi) eftirfarandi mótorgerðir væru notaðar og afhverju:
   1. Brushed DC Motor.
   1. Brushless DC motor.
   1. Stepper motor.
      
