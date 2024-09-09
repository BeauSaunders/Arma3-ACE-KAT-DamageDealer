# Arma3-ACE-KAT-DamageDealer

## ZeusCharacterInit
For use in a character's init box in the Zeus Interface:
![ZeusCharacterInitbox](https://github.com/user-attachments/assets/93ad0b61-a22a-4e75-99e6-879525f4f5d9)

> Ensure you set the execution mode to T for Target

### Modification
To execute a certain number of times change '_woundCount = random 8;' on line 6 to (5 representing the number of wounds you want to deal):
_woundCount = 5;

To execute specific instructions, you can add the following below the 'selectRandom' lines (line 14):
_part = "body";
_woundType = "bullet";
