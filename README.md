# ECE387-Midterm
Zhiyun Deng

Sensor:Vibration Sensor SW-420

Dimension: 3.2cm x 1.4cm;
Working voltage: 3.3V to 5V;
Output form: digital switch output (0 and 1);
On-board indicator LED to show the results;
On-board LM393 chip;

Principle:

Usually at any angle switch is ON state, by the vibration or movement, the rollers of
the conduction current in the switch will produce a movement or vibration, causing the
current through the disconnect or the rise of the resistance and trigger circuit. The
characteristics of this switch is usually general in the conduction state briefly disconnected
resistant to vibration, so it's high sensitivity settings by IC, customers according to their
sensitivity requirements for adjustments. 

how it work?

Connect Vcc pin of sensor board to 5V pin of Arduino board, connect Gnd pin to Gnd
pin of Arduino, Connect DO output signal pin of sensor board to Arduino digital pin D3. Do
some calibration and adjust the sensitivity threshold, then upload the following sketch to
Arduino board. 

My idea


We can put it on the bedside table, or some where close to your alarm clock. When the alarm goes off, the accompanying vibration causes the vibration sensor which touches the same table, vibrates, and the LEDs will turn on.The finally idea is combined with wireless charging desk lamp. When we sleep, we set up the alarm and charge the phone. In the morning, when the alarm goes off, vibration will turn on the lamp, which will help you waking faster. This combination no only for alarm clock, it also is a easy way to turn on your light. Imagine you got up in the middle of the night. It’s not very easy to find the light switch in the dark. At this time, you only need to tap the table and the light will turn on.

Other Application Ideas

 Vibration detecting
 Burglary protection system
 Object Movement detecting
 Triggering effect reported theft alarm
 Smart car
 Earthquake alarm
 Motorcycle alarm
