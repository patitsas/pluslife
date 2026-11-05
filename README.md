# How operate a covid PCR test with a Pluslife Minidock device

## Doing a test
**Before starting:** avoid eating/drinking for 60 minutes before any throat/cheek swab. The test is sensitive to pH changes due to food/drink.

1. Check the expiration date on the test. Expired tests are likely to provide invalid results.
1. Plug in the minidock testing device.
	* The usb-c port is for data, not power. Use the DC port.
	* It's a sensitive piece of equipment. Don't plug it into a cheap USB wall adapter. 
	* Virus.sucks recommends plugging it into a power bank from a reputable manufacturer, just in case there is a power outage.
2. Press the button on the minidock for it to turn on. The minidock will beep and the power LED will flash red.
	* It will take about two minutes to warm up. It will beep again once it has warmed up, and the power LED will turn blue.

2. If running test by computer, connect the minidock to the [Pluslife Analyzer](https://virus.sucks/pluslife_app/). Using the Analyzer is optional but recommended, as it will give you much more information.
	* You'll need a Chrome-based browser like Chromium.
	* If on Linux, open Chromium through the terminal with: 
	```
	chromium-browser --enable-* features=webBluetooth
	```
	
	* Then go to virus.sucks and then click [Analyzer](https://virus.sucks/pluslife_app/)
	* In the [Pluslife Analyzer](https://virus.sucks/pluslife_app/), you can connect to the minidock via Bluetooth.

3. Wash hands, dry thoroughly, and put on disposable gloves.
	* The test cards should not be touched with bare hands. The oils of the skin will mess up the test.

4. Set up the other components: 
	1. One vial of buffer solution
	2. One blue top for vial
	3. One swab per tested individual
	4. One biohazard bag
	4. The teal stand. Put test card and vial into the appropriate holes in the teal stand. Find somewhere suitable to put the blue top for the vial.

5. Blow nose thoroughly before doing a nose swab! Excess mucus will gum up the vial.

6. Swab mouth/throat and nostrils.
	* If testing self: change gloves if you touched your face at this stage.
	* If pool testing: repeat with every test subject

7. Put swab in vial. Stir it around, making 10 revolutions. Squeeze the vial as you remove the swab. Don’t linger!
	* It does not need time to linger like a rapid antigen test does.
	* If you wait too long, the mucus will congeal(?), and block the blue vial top.
	* If pool testing: repeat with the other swabs. 

8. Place used swabs into the biohazard bag.
8. Screw the blue vial top onto the vial.
8. Invert, and **softly** tap the vial with the back of your finger. Tap it five times to **gently** stir. Then check for air bubbles.
	* The goal is to mix, but not to introduce air bubbles.
	* If uncertain, err on the side of less force/mixing than too much!
	* If you see any air bubbles, put the vial back in the stand and wait 2-5 seconds for the air bubbles to subside.

9. Squeeze droplets into the test card until liquid level in the test card is between the two lines:

	![](testcardlines.svg)

10. Wait 15 seconds. Then screw cap onto the test card. 

11. Press the “button” of the cap of the test card. This will push the liquid into the small circular chambers of the test card.

13. **Gently** flick the test card 10 times. The goal is to mix it, but not to add air bubbles.
	* "Flick" is really more tapping it with the back of your finger, rather than spring loading your index finger against your thumb.
	* The manual says to "shake it up and down for 10 times in about 5 seconds". You can do that instead, but don't be vigourous! Again, you want to avoid air bubbles.

14. Verify that the test chamber is not full of bubbles. 
	* There are seven circular chambers in the test card that surround the central reservoir. Each chamber corresponds to a channel in the testing process.
	* If there is a bubble in a single chamber, the channel associated with that chamber will be affected. The control chamber is the one at the bottom in the middle.
	* Air bubbles can be hard to see! You may need to pick up the test card and look at it with a light source behind it. You may want a magnifying glass.
	* The buffer solution is sensitive to light. Don't expose it to bright light for more than a few seconds.

15. Verify that the "button" of the test card is still in the downwards position.

15. Place card into the minidock and close lid.

16. Begin the test by either:
	* Starting the test through the Pluslife Analyzer web interface.
	* Pressing the button on the minidock (this will not give you the curve)

17. A negative test takes 35 minutes. A positive test can take less time, as the test will stop as soon as the positive is detected.

18. Once the test is complete, remove the test card and place it in the biohazard bag.
	* The test card should not be left in the minidock after the test. The liquid inside will slowly evaporate due to the heat of the minidock.

19. Unplug the minidock.
	* The minidock does not automatically turn off on its own. The heater will keep warming the device indefinitely.


## Interpreting test results

* [Examples of what positive test curves look like](https://www.reddit.com/r/PlusLife/comments/1hpljs5/what_positive_pluslife_tests_look_like/)
* [Examples of what negative test curves look like](https://www.reddit.com/r/PlusLife/comments/1hplo7g/this_is_what_negative_pluslife_results_look_like/)
* [Virus.sucks FAQ](https://virus.sucks/pluslife_en/)

## References
* The SARS-CoV-2 Nucleic Acid Testing Card manual provided PlusLife
* [Virus.sucks FAQ](https://virus.sucks/pluslife_en/)

## Contributing to this page
If you have suggestions for improving this page, I welcome pull requests!
