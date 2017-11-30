# Crystals-Collector

Sources:

    Background Images:

Diamond-background.jpeg -
https://www.google.com/search?tbs=simg%3Am00&tbnid=8TIJasmacNlAGM%3A&docid=0FwTsw0DQdOOPM&tbm=isch&ved=0ahUKEwiX4cbIp-TXAhUMxWMKHVVVB44QhxwICA&biw=1440&bih=756&dpr=2#imgrc=8TIJasmacNlAGM:

nice-pic.jpeg -
https://www.google.com/search?q=scary+maze+game+face&tbm=isch&tbs=simg:CAQSmwEJp2rGCgyg5PkajwELEKjU2AQaCAgXCD0IFQgADAsQsIynCBpiCmAIAxIo7BaKDLQfxxaQF-sW8wSHDMgWlA66LbktnTqeOrUtwy2-Lb0tti24LRowgGu5OSdSfij5Hu8g8CLICMlkw7_1WqLjfjAW-ZAVox7-XoiS3RoT01ffxrH16E0cFIAQMCxCOrv4IGgoKCAgBEgR5VWzqDA&sa=X&ved=0ahUKEwiRxrya8ebXAhUI42MKHYSGAucQ2A4IJygB&biw=1440&bih=757#imgrc=u-wfA11cwa85HM:

    Gems:

Gem Buttons -
https://www.123rf.com/photo_42515202_stock-vector-set-of-fancy-modern-faceted-square-buttons-vector-isolated-elements.html?fromid=SThEVmxod1JKZkFWN1h4ayswZENsUT09

    Audio Files:

Air Horn -
http://www.instantrapairhorn.com/

Nice Noise -
https://www.freesoundeffects.com/free-sounds/screams-10094/ .. (nmh_scream1)




Side Notes:

    N: Delete the 3 lines below 'Good game' to make the game 'normal' ;)

    Q: Can I make a function the makes the panels with just a few inputs to shorten bootstrap code
    for things like wins, loses, current number and target number?

    Q: Are the sound files in the right place? Also, are they in the right tag?

    Q: I tried adding a delayed promt to go after 2 seconds from when the player loses asking if they want to play again. It worked, however, it did not allow for the animation / noise to play on game over.

        setTimeout(function(){
            if(confirm("Play again?")) {
                resetGame();
            }
        },2000);

    PN: clearfix*