# Manual-PS4-Trophy-Unlcoker
Explanation on a method on how to unlock trophies on the PS4

## Requirements 
np_trophy
a target(for this i used CUSA00184 [Angry Birds Star Wars]

## Step 1 
Decrypt the pkg of the game (passcode should be all zeros)
From the decrypted files you will need the following 
* basically the whole /sc0/ directory just dont use the changeinfo directory ,psresereved.dat or the trophy directory there
* the trophy directory (can be obtrained via ftp)

Now we can start you need to open up nptitle.dat in a hex viewer and grab the nptitleid and the secret

Now you need to place those values inside np_trophy in the NpTitleId and NpTitleSecret variables

Then you can build the pkg and thats it press x 
Select your trophy and click unlock 





  

