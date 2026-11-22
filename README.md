# Unit 6 Team Hangman

A two team Hangman game I made for ARIN 320, Unit 6 (Domain Specific AI Applications and Case Studies). We play it live in class on one shared screen.

**Play it here:** https://teamgalacticdisc.github.io/unit6-hangman/

## How it works

Every wrong letter adds a piece to an AI robot. Eight wrong letters and the robot powers on, which ends the round. I picked a robot because this is an AI class, so the thing being built should be AI too.

- Teams take turns guessing letters. A right letter scores points and you keep going. A wrong letter hands the turn to the other team.
- On your turn you can try to solve the whole word. Big points if you get it, and you lose points if you miss.
- Each team gets one steal (solve the other team's word on their turn) and one lifeline (reveal a letter for free).
- Whoever wins the word gets a bonus question from the unit.

## Why I built it this way

- **Every word comes straight from Unit 6.** I didn't want made up terms, so each word lists the Unit 6 page and section it came from. You can check any of them.
- **One file, no install.** The whole game is one HTML page, so it opens in any browser on any classroom computer.
- **Scores survive a refresh.** If someone bumps the screen and the page reloads, nobody loses their points. The scores save in the browser.
- **The teacher stays in control.** There's a teacher panel to add or take away points, undo a mistake, skip a word, and download the final scores as a CSV file.
