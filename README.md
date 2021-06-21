# Caesar-Cipher
A caesar cipher! This will encode a block of text by swapping each character with another character along a set interval, i

With this code, you should be able to paste any block of text on line 27 (or between the triple parenthesis) and change the number on line 32 in order to encode the block of text with a caesar cipher, according to the number you chose to input. It removes all spaces and punctuation, as well as changing all capitals to lower case. This produces a long string of text, which makes it extra confusing (as a cipher should be!)

In this instance, I encoded the following text:
"
This cosmic dance of bursting decadence and withheld permissions, 
twists all our arms collectively, but if sweetness can win, and it can, 
then I'll still be here tomorrow to high-five you yesterday, my friend.
"

at an interval of +10, which produces as the following:
"
drscmycwsmnkxmoyplebcdsxqnomknoxmokxngsdrrovnzobwsccsyxcdgscdckvvyebkbwcmyvvomdsfoviledspcgoodxoccmkxgsxkxnsdmkxdroxsvvcdsvvlorobodywybbygdyrsqrpsfoiyeiocdobnkiwipbsoxn
"

You can use this same code to decode a caesar-ciphered message by pasting the block of encoded text between the triple parenthesis and changing the number on line 32 to the negative of the number which was used to encode it in the first place. 
In this case, you would decode by inputting "-10" because I initially encoded it at an interval of +10.
