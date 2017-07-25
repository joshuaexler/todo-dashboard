Todo Daily Dashboard - version 1.12
Author: Joshua Exler (https://www.joshua.consulting). Questions? Contact joshua (at) joshua (dot) consulting
Most recent edit: July 25th, 2017
License: MIT. See LICENSE.txt.

PROMINENTLY USED LIBRARIES:
Todoist Javascript API by OiYouYeahYou: https://github.com/OiYouYeahYou/Todoist.js
ChartNew.js by FVANCOP: https://github.com/FVANCOP/ChartNew.js

Icons used for task pictograms are from The Noun Project (https://nounproject.com)

CHANGELOG
v. 1.12: Pie chart labels can no longer overlap
v. 1.11: Changed first chart to a pie chart and centered all content on page
v. 1.1: Added pictogram hover tooltips, a 'life coach' algorithm to suggest tasks weighted by priority, and an algorithm to suggest tasks randomly
v. 1.09: The area containing tasks-as-pictograms is now called 'Tasks Remaining Today' and is styled more similarly to the graphs' styling
v. 1.08: Tweaked priority colors and styling of pictograms
v. 1.07: Mobile compatibility restored and fully debugged
v. 1.06: 'Syncing' message restored to graphs
v. 1.05: Quieter syncing - Graphs refresh more quickly and without 'syncing' message overlay. Sync countdown is now hidden: it's still in the header, but its font color is the same as the header bg.
v. 1.04: New feature - Daily tasks are displayed at the bottom of the screen in a pictogram format
v. 1.03: Attempting to rework sync function to debug timer when sync takes longer than 1 second
v. 1.02: Fixed bug where text weight would increase upon page resize in graphs #1 and #2
v. 1.01: Fixed bug where graph widths would increase upon page resize
v. 1.00: First upload and public release

KNOWN BUGS (ranked in order of triage sort)
- The number of total tasks completed today updates to zero approximately fifteen minutes after midnight, regardless of timezone etc.
