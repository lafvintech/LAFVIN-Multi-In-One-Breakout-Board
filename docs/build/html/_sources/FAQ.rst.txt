Frequently Asked Question
==========================

**Need help? Please see here first.**

- To help you quickly resolve your issues, we have compiled frequently asked questions and troubleshooting methods below. Please try self-troubleshooting first, as this is usually the most efficient way to solve problems.

.. raw:: html

   <div style="margin-top: 30px;"></div>

- If you cannot find a solution here, please feel free to contact our after-sales team for further technical support.

----

**1.How do I choose the supply voltage?**

 - The breakout board provides two voltage options: 3.3V and 5V. You can select the desired voltage by adjusting the jumper cap on the voltage selection pins.
 
 - Ensure that the selected voltage matches the requirements of your development board and any connected modules.

----

**2.How do the GPIO indicator LEDs work?**

 - Each pin is equipped with an indicator LED that shows the voltage state of the development board's pin.

 - When a pin is commanded to output a high or low voltage, the indicator LED changes accordingly.

 - Certain pins on the board may remain unused; these pins exist in a floating state—potentially registering as either high or low voltage—causing the corresponding indicator LEDs to light up or turn off.

 - If you do not want the indicator LED to be on or off, you can control the pin via programming to output either a high or low voltage.

----

**3.The breakout board does not power on.**
 - Check that the DC jack polarity is correct and that the external adapter provides sufficient voltage (recommend 9V or higher).
 - Verify the power switch is turned on and the power indicator LED is lit.
 - Ensure jumper caps are set to the correct output voltage (3.3V or 5V) matching your development board.

----

**4.Pins are loose or signals are unstable.**
 - Make sure the development board is fully seated in the female headers and aligned properly.
 - Use screw terminals or secure connectors when performing experiments that involve movement.
 - Check for bent or damaged header pins and replace or realign if necessary.

----

**5.Can I use 3.3V modules with this breakout board?**
 - Yes. Set the voltage selection jumper to `3.3V` before connecting 3.3V modules.
 - Never mix modules requiring different supply voltages on the same power rail without proper level shifting.

----

**6.Can I use this breakout board with my own custom development board?**
 - Yes. Ensure your custom board's pinout matches the breakout board's headers and that the voltage levels are compatible.
 - Double-check the power requirements and jumper settings before connecting.

----
