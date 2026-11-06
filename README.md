# How to operate a covid PCR test with a Pluslife Minidock device

## Doing a test
**Before starting:** avoid eating/drinking for 60 minutes before any throat/cheek swab. The test is sensitive to pH changes due to food/drink.

1. Check the expiration date on the test. Expired tests are likely to provide invalid results.
2. Place the minidock on a stable, level surface.
1. Plug in the minidock testing device.
	* The USB-C port is for data, not power. Use the DC port.
	* It's a sensitive piece of equipment. Don't plug it into a cheap USB wall adapter. 
	* Virus.sucks recommends [plugging it into a power bank](https://virus.sucks/pluslife_en/#tips-and-tricks) from a reputable manufacturer, just in case there is a power outage.
2. Press the button on the minidock for it to turn on. The minidock will beep and the power LED will flash red.
	* It will take about two minutes to warm up. It will beep again once it has warmed up, and the power LED will turn blue.

2. If running test by computer, connect the minidock to the [Pluslife Analyzer](https://virus.sucks/pluslife_app/). Using the Analyzer is optional but recommended, as it will give you much more information.
	* You'll need a Chrome-based browser like Chromium.
	* If on Linux, open Chromium through the terminal with: 
	```
	chromium-browser --enable-features=WebBluetooth
	```
	
	* Then go to virus.sucks and then click [Analyzer](https://virus.sucks/pluslife_app/)
	* In the [Pluslife Analyzer](https://virus.sucks/pluslife_app/), you can connect to the minidock via Bluetooth.

3. Wash hands, dry thoroughly, and put on disposable gloves.
	* The test cards should not be touched with bare hands. The oils of the skin can negatively affect the test.

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

9. Squeeze droplets into the test card. Have the droplets [drip down the side of the wall](https://www.reddit.com/r/PlusLife/comments/1mmes86/comment/n7y2klr/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button). Slowly fill until liquid level in the test card is between the two lines:

	![Shows two lines in the test card between the lid and the test chamber.](testcardlines.svg)

10. Wait 15 seconds. Then screw cap onto the test card. Make sure it is fully screwed on.

11. Press the “button” of the cap of the test card. This will push the liquid into the small circular chambers of the test card.

13. **Gently** flick the test card 10 times. The goal is to mix it, but not to add air bubbles.
	* "Flick" is really more tapping it with the back of your finger, rather than spring loading your index finger against your thumb.
	* Make sure you have a firm grip on the test card when flicking it! You don't want to drop the test card.
	* The manual says to "shake it up and down for 10 times in about 5 seconds". You can do that instead, but don't be vigourous! Again, you want to avoid air bubbles.

14. Verify that the test chamber does not have any large air bubbles. 
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
	* The minidock will beep again when the test is complete.

18. Once the test is complete, remove the test card and place it in the biohazard bag.
	* The test card should not be left in the minidock after the test. The liquid inside will slowly evaporate due to the heat of the minidock.

19. Unplug the minidock.
	* The minidock does not automatically turn off on its own. The heater will keep warming the device indefinitely.

## Interpreting test results

* [Examples of what positive test curves look like](https://www.reddit.com/r/PlusLife/comments/1hpljs5/what_positive_pluslife_tests_look_like/) assembled by 
u/SomeoneSomewhere1984 on [r/PlusLife](https://www.reddit.com/r/PlusLife/)
	* You see a sigmoid ("S") curve in a non-control channel.
* [Examples of what negative test curves look like](https://www.reddit.com/r/PlusLife/comments/1hplo7g/this_is_what_negative_pluslife_results_look_like/) assembled by 
u/SomeoneSomewhere1984 on r/PlusLife
	* Only the control (channel 4) has a sigmoid curve
* [An example of what a false positive looks like](https://www.reddit.com/r/PlusLife/comments/1xfday7/comment/19rnkrlp97yud/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) provided by u/whatself
	* Non-control channels go up, but do not look like a sigmoid curve.
* Examples of what a weak/early positive looks like: 
	* [provided by u/Secret_Gur5312](https://www.reddit.com/r/PlusLife/comments/1mqal01/example_of_weak_positive): The sigmoid curve is present, but does not surpass the threshold for a positive.
	* [provided by /u/BlueValk](https://www.reddit.com/r/PlusLife/comments/1uwcmoa/partner_has_symptoms_this_is_an_early_positive/). Also shows an sigmoid which did not surpass the threshold. The individual tested positive 25 hours later.
* [Examples of what air bubbles look like](https://virus.sucks/pluslife_en/#air-bubble-curves) by Virus.sucks
	* They look like small waves/wobbles in the line.
* Two examples of what it looks like if the cap of the test card is not properly sealed: [from u/PartyBelt585](https://www.reddit.com/r/PlusLife/comments/1x2e64n/comment/pfcw6w3/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) and [from u/underfullhbox](https://www.reddit.com/r/PlusLife/comments/1xothqx/comment/19s78hj2eq9oh/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) 
	* The control channel rises quickly, then drops suddenly. After that, it curves upwards like a typical test.  
* If you're getting unusual results, check out the [r/PlusLife](https://www.reddit.com/r/PlusLife/) subreddit!

## For more information
* [Virus.sucks](https://virus.sucks/)
* [r/PlusLife](https://www.reddit.com/r/PlusLife/)

## References
* "The SARS-CoV-2 Nucleic Acid Testing Card" manual provided by PlusLife
* ["Pluslife Mini Dock Cov-19 Test Device"](https://www.youtube.com/watch?v=olI_akQ6lN8) YouTube video provided by Audasia GmbH
* ["FAQ"](https://virus.sucks/pluslife_en/) by Virus.sucks
* ["Pluslife COVID Test Overview"](https://www.youtube.com/watch?v=AmLF43wvCvc) by Cooper Kidd
* ["techniques for avoiding air bubbles ?"](https://www.reddit.com/r/PlusLife/comments/1mmes86/techniques_for_avoiding_air_bubbles/) thread on r/PlusLife

## Contributing to this page
If you have suggestions for improving this page, I welcome pull requests!

### Open questions:
1. Multiple sources recommend that you verify whether there are air bubbles in the test card before running the test. Is there anything one can actually do to get rid of the air bubbles if they're there?
2. Best practices for mixing without introducing air bubbles: is there a technique better than gently tapping/flicking?
