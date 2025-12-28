# MOD 26

## Difficulty
Easy

## Method

1. Download the file provided in the challenge
2. Copy the encoded message from within that file
3. Use ROT13 cipher to decode the message
   - Online tool: [dCode Caesar Cipher](https://www.dcode.fr/caesar-cipher)
   - Set the shift value to 13 (ROT13)
4. You will get the flag

## Notes

ROT13 is a special case of the Caesar cipher where the shift is 13. Since the alphabet has 26 letters (MOD 26), applying ROT13 twice returns the original text.

