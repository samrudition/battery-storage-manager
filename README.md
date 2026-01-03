# Battery Storage Manager: CS50 Problem Set 0
Simulation game designed on Scratch that challenges the player to manage the battery system of a virtual data center over a 24-hour cycle. During the day, solar power charges the battery slowly, but at night, your data center draws power quickly, putting your battery at risk of running out. This is my first project on CS50. 

# Game Instructions
- Open Scratch link (https://scratch.mit.edu/projects/1243079154)
- Press the green flag to start and read the instructions.
- The simulation runs automatically. Battery charges in the daytime (hours 6–18) and drains at night.
- If your battery empties, your system will automatically buy power from the grid at a high cost!
- Press the space bar to charge the battery from the grid (+15% per press, +$15 cost). Use this strategically so the battery doesn't run out overnight.
- Press the D key to manually discharge battery power (-10% per press if needed).
- Monitor the display: The battery icon shows your charge level, the data center color changes by battery health, and the sun/sun panel show if it's daytime.

**Win by**: 
- Completing 24 hours and keeping total cost under $100, and never letting the battery stay below 10% for 5 consecutive hours.
  
**Lose if**: 
- Your total grid cost exceeds $150, or the battery stays below 10% for 5 hours.
  
When the total cost is between $100-$150, you will receive a warning message after 24 hours that the cost is high but you managed the data center fairly.



