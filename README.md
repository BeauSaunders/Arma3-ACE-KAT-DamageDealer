# Arma3-ACE-KAT-DamageDealer

## ZeusCharacterInit
For use in a character's init box in the Zeus Interface:
![ZeusCharacterInitbox](https://github.com/user-attachments/assets/a207893b-7823-4c9e-8d8b-7f516a0e39d4)

> Ensure you set the execution mode to T for Target

### Modification
To execute a certain number of times change `_woundCount = random 8;` on line 6 to (5 representing the number of wounds you want to deal):
`_woundCount = 5;`

To execute specific instructions, you can add the following below the `selectRandom` lines (line 14):
`_part = "body";`
`_woundType = "bullet";`
