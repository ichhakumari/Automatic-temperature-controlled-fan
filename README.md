# Automatic-temperature-controlled-fan
<h6> Using Arduino Step by Step Guide with Code</h6>
<img src="https://robu.in/wp-content/uploads/2021/02/ckt2-1024x683.jpg" alt="img">
<h4> INTRODUCTION </h4>
<P>Temperature controlling is required in many places such as server rooms, houses, industries, etc. So this project can be very useful in understanding the basics, how you can control the temperature at your home. You can take this as a DIY project which can be used anywhere. Here the Temperature controlled fan will act to the temperature changes.</P>

<P>We have also written a blog on what temperature sensors are, if you are interested feel free to read that as well to understand more about these types of sensors.</P>

<P>We are going to do this with a DHT11 temperature and humidity sensor. It can be done in various other ways as well. With a thermistor or other sensors like a contactless temperature sensor. But thermistor usually needs contact of the surface and contactless sensors can be costly. While DHT11 is a cost-effective sensor.</P>

<P>In this article, we are going to discuss making a temperature-controlled fan using Arduino. With this circuit, we will be able to change the fan speed in our home or any place according to the room temperature and also display the temperature and fan speed changes on a 16x2 LCD display. To do this we will be using an Arduino UNO Board, LCD, DHT11 sensor Module, and DC fan. Let's get started.</P>

<H4>How does it Work? </H4>

<H6>This project works in three parts -</H6>
<P>n the first step, the sensor senses the temperature by temperature and humidity sensor namely DHT11.</P>

<P>In the second step, the sensor's output is taken and conversion of temperature value into a suitable number in Celsius scale is done. The fan speed is controlled by using PWM signals. And last part of the system shows humidity and temperature on LCD and Fan runs.</P>

<P>Then we have programmed our Arduino according to the requirements. Working on this is very simple. We have generated PWM from Arduino and put it at the base terminal of the transistor. Then transistor generates voltage with respect to the PWM input.</P>

<H4>Connections</H4>

<OL> <LI><B>  Gather all these components</B></LI>
<OL>
  <LI>  Components required</LI>
   <UL>
        
<LI>Arduino UNO</LI>
<LI>USB A to B</LI>
<LI>Breadboard</LI>
<LI>DHT11 sensor</LI>
<LI>DC Fan</LI>
<LI>2n2222 transistor</LI>
<LI>16x2 LCD</LI>
<LI>Connecting wires</LI>
Connections of this are very easy to do, here an LCD is connected for displaying temperature and Fan speed Status.
</UL></OL>
<LI><B>LCD connection with Arduino</B></LI>
LCD is directly connected to Arduino (Check this tutorial for more details: LCD Interfacing with Arduino Uno). Connect pins of LCD- RS, EN, D4, D5, D6, and D7 to Arduino's digital pin numbers 7, 6, 5, 4, 3, and 2.
<LI><B> DHT 11 temperature and humidity sensor connection</B></LI>
And a DHT11 sensor module is also connected to digital pin 12 of Arduino. Digital pin 9 is used for controlling fan speed through the transistor.
<IMG-SRC="https://robu.in/wp-content/uploads/2021/02/circuit-1024x576.png" ALT="CIRCUIT DIAGRAM">
  <LI><B> Upload the code </B></LI>

The below section is for the code. Here the first table gives you an idea of what PWM value will be the speed of the fan. You can change values according to your need.
</OL>
<H4> FINAL WORDS</H4>
<P> we learned about, how we can make a temperature-controlled fan circuit. Using an Arduino, DHT11, and few other components. Which can be used pretty much any place where temperature needs to be maintained at specific levels. Like in some industries, houses, etc. We checked how it actually works and we also learned how to code for a temperature-controlled fan.</P>


