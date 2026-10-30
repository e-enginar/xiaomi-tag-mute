# xiaomi-tag-mute
xiaomi_tag.jpg
explaining how I managed to mute the speaker and turn off nfc on my xiaomi tag
disclaimer:
This guide is for informational and educational purposes only.
this operation is obviously out of warranty.

*STEP 1: TEARDOWN*
*verification test*
before going further, please test these functions:
press the hidden button where the xiaomi text is, it should make a beep sound when you press it(you dont need to hold press)
Bring the back of your phone close to the device; you should immediately receive a notification on your phone stating that NFC has been detected.(if this is not working look at your phones NFC settings. Also your phone may not have an NFC, just goole it.)

There are mainly 4 parts.
all_parts.jpg
*1)* Front plate(covering the battery, theres also part of the hidden button and bluetooth mod)
*2)* Back plate( the speaker and nfc sensor is in this part)
*3)* Mid case(A large part that holds the battery, independent of the top and bottom plates.)
*4)* Gray circle(An accessory that contains no circuitry and serves solely to hang the device somewhere. however device might lose its waterproof and dustproof if you dont use it.)

*warning:*
Especially if you are using a metal object for prying, plastic can deform very easily.

you can see a gap in right side of the tag to open battery compartment.
just pry open the front plate with your finger or with a screwdriver.
all_parts_before_back_plate.jpg
After taking off the battery its gonna look like this



you can see the clips of the gray circle, try to set free some clips then it will go off when you pull it from the hanging section.
circle_out.jpg

*Warning for next step*: 
if you look closely theres white waterproof gasket at the intersection point of the back plate and mid case, its looks like theres no glue between gasket and back plate, its just glued to the case.
so if you dont want to lose it waterproof you should be careful when opening it.
gasket_gap.jpg

you can use this gap in next step to open it


the back plate and mid case is glued from inside. you should heat the glue first. I simply use a 1200W hairdryer, hold it to middle of the case 10-15 seconds(it can blown away if you hold it to sides) then quickly try to pry it open, if you cant take apart it in 10 seconds, heat it back and try again.
back_plate_out
If you managed to separate these parts, congratulations! you tear it down compleatly(or at least enough to reach nfc and speaker)

**STEP 2: MODIFYNG**
black_plate_pins.jpg
as you can see there 2 pair of pins(on mid case) and their respetive pads(on backplate).
Pink circled pair is power path to buzzer and red circled pair is nfc's power. If we simply block the path by adding a isolation layer between these pins and peds, respetive function will shut off.
these functions can work seperatly. so you can use it with buzzer off, nfc on; buzzer on, nfc off. or both off. just put an electric tape on the peds you want to shut off.

back_plate_covered.jpg

*An referrence image that The NFC pads are completely covered with electrical tape. As for the buzzer, while the ground pad is covered, a portion of the positive (+) pad remains exposed;
however, since the ground pin is not in contact with its pad, the circuit is not completed, and the function will not work.*
*Warning:*
Dont forget the pins in mid case can puncture the isolation material. I recommend using two layers of tape.

after you finish isolating; Simply put the battery back, close the front plate and press the back plate and mid case together with your hand.
at that point if you closed the speaker function the device will not make a sound when your press the hidden button.
if you closed NFC function you shouldnt see an notice when you bring the phone to device.
if the function(s) are still on, look for an puncture on tape.
if it works how you want, next step is closing the parts back.

**STEP 3: reintegration**
you need to glue back plate and mid case back.
glue.jpg
you can use a super glue to the square-patterned area on mid case,
Next, attach the gray circle to its clips
(if you do not like the gray circle or need to fit it into a tight space, you can skip this step; the version without the circle is shown below, though please note that it will likely lose its water-resistant property if used this way).
no_circle.jpg
then insert battery and close front plate back.
