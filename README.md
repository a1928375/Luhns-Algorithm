# Luhns-Algorithm

Concise definition of the Luhn checksum:

"For a card with an even number of digits, double every odd numbered digit and subtract 9 if the product is greater than 9. Add up all 
the even digits as well as the doubled-odd digits, and the result must be a multiple of 10 or it's not a valid card. If the card has an 
odd number of digits, perform the same addition doubling the even numbered digits instead."
 
Implement the Luhn Checksum algorithm as described above. is_luhn_valid takes a credit card number as input and verifies whether it is valid or not. If it is valid, it returns True, otherwise it returns False.
