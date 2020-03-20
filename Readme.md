Random draw function for Lottery Engine
-------------

This script (method) is used in the Lottery Engine to randomly select winners' wallets from the source list of wallets of lottery draw participants.

This method is called automatically at the moment when the Lottery Engine determined that all lottery tickets were purchased. Then the list of winning wallets is immediately published in the telegram channel (chat) where the lottery is held.

A few seconds elapse between the moment of the purchase of the last lottery ticket of the draw and the drawing together with the publication of the list of winners' wallets. Thus, manual intervention in the results of the draw becomes impossible.

Requires: PHP 7.x
