# CC3-MPI-26-3124-Satellite-Board
The “CC3-MPI-26-3124-Satellite-Board-CoCo-3-Upgrade-2009-V1RA” is a clone of the “Part # AXX-7119 Satellite Board for 26-3124” Multi-Pak Interface CoCo 3 upgrade with the additional feature of being switchable between CoCo 1,2 or 3 mode.

There is an OSHPark Page Here: https://oshpark.com/shared_projects/nOLH7Sm2

Note: the following installation instructions are provided as information
only, and the installer assumes all responsibility in dealing with this
modification.  If you are not absolutely sure you can do this 
modification, and can fix anything you accidently break, it is HIGHLY
suggested you instead take your Multipak Interface to Radio Shack and let 
them have the modification done by their service technicians.  The cost
should be somewhere around $30.

  1. Remove the MPI case
  2. Remove the three screws holding the logic board to the bottom case, 
  leaving the transformer connected.  Remove all the metal clips holding 
  the shield to the bottom of the PCB, noting their positions.  Remove 
  the shield.  This is to avoid melting through the shield insulation 
  while soldering.
  3. Cut the trace coming from pin 52 of IC6 that connects pin 52 of IC6 
  to pin 19 of IC1.
  4. Position the satellite board over IC6, components up, with the 7 
  wires facing towards the card edge.
  5. Connect the 3 yellow wires to IC4 pins 3,9, and 11.  Any order is 
  fine.
  6. Connect the white wire to IC6 pin 52, taking care not to short the 
  leads of IC6.
  7. Connect the blue wire to IC1 pin 19.
  8. Connect the black wire to IC5 pin 8.
  9. Connect the red wire to IC5 pin 16.
  10. Replace the shield and two of the logic board screws.. the one 
  nearest the power switch, and the one near the selector switch.
  11. Place the plastic spacer over the hole for the third screw. 
  Position the hole in the satellite board over the spacer with the 
  components up.  Insert the screw into the board and tighten.  The board 
  must be positioned parallel to the edge card connector so that it fits 
  into the channel between the cabinet top and the cartridge frame.  
  Replace the cabinent top.
  12. Test the unit by connecting it to a CoCo, installing a cartridge in 
  each slot, and checking to see that each slot is selectable and 
  accessable.

Please note: This is derived from an original design by "Little" John Eric and/or his father "Big" John Robert (J.R.) by "Uncle" Robert Allen. It should be thoroughly scrutinized and verified prior to actual use of any kind. DISCLAIMER: The following article is provided for informational purposes only. Any attempt to modify your computer without the proper skills to do so may void your computer. Any attempt to modify your computer without unplugging it first may void you. This Information is provided "as-is" with no guarantee of fitness for any purpose, either explicit or implied. We disclaim any and all responsibility for losses incurred through the use of this information. By using this information, you are deemed to have accepted these conditions of use, and you agree NOT to sue us. CLARIFICATION: The above disclaimer states as plainly as possible that if you decide to make use of any of the information contained within this document that you do so at your own risk. Designing hardware for the CoCo (ColorComputer) and other vintage hardware is a hobby of ours and is not motivated by any desire of profits. As this is a not for profit venture, obviously we can't afford not to disclaim the use of this information.

 PLEASE NOTE: THIS VERSION HAS NOT YET BEEN TESTED. 
