I have designed another RF extender board with HMC849 as RF switch, first measurements looked very good. The plan is to design an RF board up to 23cm, which then has 3 coupler inputs. Some adjustments have to be made to the software, so for the time being a version with two coupler inputs and AD8307.
The question has been asked why I am not using PE4259 as in the original design.
It is very difficult to get original working PE4259, I had ordered many from ebay, Ali etc, all were fakes.
Then I found the test boards with HMC 349/849, you can easily test them and make sure they work.
Since I have a hot air soldering station, it was very easy to take these tested ICs and place them on my board.
I also tried soldering them on with a soldering iron, which also worked, and I added a 2mm VIA to the ground plane under the HMC.

-In the REV3.6 the 74HC04 was removed, this was only found in the REV3.5.
-Operating the HMC with 5V did not bring any significant improvement.
