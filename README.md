# Battle Objective Point

## Overview
Arduino code for airsoft style capture points. These capture points can be programmed for various game modes to expand the options of games that can be played for a typical airsoft match.

## Hardware

## Gamemodes
1. Acumulate
  - Overview: Acumulate time by controlling the area around the OP and holding down your teams button.
  - Setup:
  - Rules:
  - Win condition: Have the most time on the clock(s) after the given time.

2. Capture
  - Overview: Capture the OP by pressing your teams button.
  - Setup:
  - Rules:
  - Win condition: Capture the most OPs by the end of the game to be the winner.
  
3. Count down
  - Overview: Be the first team to run out the clock on each OP.
  - Setup:
  - Rules:
  - Win condition: Be the first team to capture the OP by running out your team's clock, most OPs captured wins.
  
4. Team respawn
  - Overview: Each OP acts as a team respawn point, when a team member respawns the team count drops.
  - Setup:
  - Rules:
  - Win condition: Respawn till your team's counter runs out, last team standing wins.

5. Virus
  - Overview: Using an arduino nano, capture the points by uploading your teams 'virus'.
  - Setup:
  - Rules:
  - Win condition: Team with the most uploads wins.

## Software

## Upcoming

### Brainstorm
**Key:**<br/>
*GM = Game Mode/Idea*<br/>
*F = Feature*

**GM** - Acumulate time: Hold your teams button to accumulate time<br/>
**GM** - Timer count down: win by being the first team to count down the timer on the objective<br/>
**F** - SubGHz tranciever: for long distance comunication and remote programming<br/>
**F** - Tranciever hub: Central hub for setting the fields game mode, parameters, start/stop time, etc.<br/>
