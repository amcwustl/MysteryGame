# Mystery Game - Midnight Marauder

An interactive, browser-based, point and click / text based, whodunit murder mystery game that engages users in a captivating narrative experience. Utilizing vanilla HTML, CSS, and JavaScript, the game features a small but eclectic cast of characters to interact with that challenges players to solve the mystery using critical thinking, and problem-solving.

## Features

- **Intro Page:**
  1. Dynamic Typing Animation: As soon as the web page loads, a dynamic typing animation displays the introduction to the story.
  2. User Profile: Users can input their name, and based on their interactions, certain elements of the story may change.
  3. Local Storage: User information is stored in the browser's local storage, ensuring that the story remains consistent even after a browser refresh.

- **Main Game:**
  1. Display Evidence and Alibi for Each Character:
      - Players can view individual logs for each character which includes their evidence and alibi.
      - Additional evidence or alibis can be appended to a character's log, presumably based on the player's discoveries or choices.
  2. Open/Close Logbook:
      - The logbook can be toggled open or closed by interacting with a specific game element (not defined in the provided snippets).
      - When opened, two logbooks (logbook1 and logbook2) and a notebook (noteBook) become visible, displaying the updated logs for each character.
      - When closed, the logbooks and notebook are hidden.
  3. View Instructions:
      - Players can view game instructions by clicking on an element with the ID show-instructions.
      - The instructions are displayed in a modal which can be closed by clicking an element with the ID closeButton.
  4. Initiate Character Interaction:
      - Players can approach a character and initiate an interaction, presumably by clicking on the character or pressing a specific key.
  5. Gather Evidence or Alibi:
      - Upon successful interaction, the character may reveal new evidence or provide an alibi related to an ongoing investigation or event.
      - This information is then saved to the user's profile (as per the provided code, in variables like user.alexanderAlibi or user.jonathanEvidence).
  6. Update Logbook:
      - After gathering new evidence or alibi, the player can open the logbook to review the newly collected information.
      - The logbook updates in real-time with each new piece of evidence or alibi gathered.
  7. Accuse Suspects:
      - After gathering enough evidence, the player can choose a suspect to accuse of the crime.
      - Upon successful solving, a unique message will be displayed. Incorrect guesses lead to more information being provided and additional guesses up to 3 total.

## Project Authors

Jennifer Sung, Aaron Clark, and Dylan Cooper


## Original Art

All original art provided by [Jack Panic](https://linktr.ee/thedungeonmanager?utm_source=linktree_profile_share&ltsid=33927ca6-b344-4bc8-942f-45fce8acc42d)

## References

Code commenting help provided by ChatGPT.  Any Code snippets provided by chatGPT are commented in the code as such.
