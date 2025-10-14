.-.   .-. .----. .-. .-. .----..---. .----..----.  .---.  .--.  .-.   .-..----..----. 
|  `.'  |/  {}  \|  `| |{ {__ {_   _}| {_  | {}  }{_   _}/ {} \ |  `.'  || {_  | {}  }
| |\ /| |\      /| |\  |.-._} } | |  | {__ | .-. \  | | /  /\  \| |\ /| || {__ | .-. \
`-' ` `-' `----' `-' `-'`----'  `-'  `----'`-' `-'  `-' `-'  `-'`-' ` `-'`----'`-' `-'

Monster Tamer Slots
This is a simulated gambling game for Dungeons & Dragons or any other TTRPG or just for shits and giggles.

Do NOT use this for any real gambling if doing such a thing is illegal where you live.

If it isn't illegal where you live then knock yourself out, see if I care.

Tweaking

Starting on line 95 you can change probability-related stats:

LOOSENESS - This determines how often players get 3-of-a-kind. The 7% I have it set to is what I found to be enough that my players can get some good wins but won't just pump endless gold into the machine and becoming multi-billionaires.

TWO_KIND_PAY_MULT - How much two matching symbols wins. Currently you win 75% of your bet, slowing down losses, but still accumulating.

MAJOR_THRESHOLD - How much of a multipier you have to get in order to trigger the Major Win sound effect.

HIGH_PAY_BIAS - set low for even odds for all symbols, set higher to favor lower payouts.

Reskinning
If D&D isn't your thing and you'd prefer the reels were themed around, say, tropical fish, historical trains, or famous people named gary, you can do that and more easily. Just go to the /images folder and create new images for 1.png through 12.png. 1 being the lowest value (goblin, in this case) and 12 being the highest (terrasque). If you want to change out the sounds here's what they are:
1.wav inserting a coin
2.wav spinning the reels
3.wav minor win
4.wav major win

Images and sounds should just be able to be swapped out and they'll work. The machine will still identify them as the original theme d&d creatures though. To change that go to lines 105 and 106 in the index.html and switch out the labels.

instructions.pdf
Send these to your players if they want to know more about the payouts. You can also print them out if you work in an office that has free use of color printers. What they don't know won't hurt them.

Legal notice

I accept no legal responsibility if you decide to use this in stupid, illegal ways it was never intended for.

AI Policy

Yes, I used AI in the creation of this and your opinions on that fact do not matter to me even a little. <3
