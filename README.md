# C# Character Generator

- *AAB Project Code b722970d*
- *Code Along Project 2*

## Requirements

1. A `CharacterGenerator.exe` file that can be run on a Windows machine
1. A main menu that allows users to:
    - Generate a New Character
    - Display the Current Character
    - Add the Current Character to the Party
    - Display the Current Party
    - Exit
1. New Character Generation
    1. Allows entering the following data:
        - Enter the Character's name
        - Enter the Player's name
        - Select the Character's ancestry
            - Options: Human, Elf, Halfling, Dwarf, Half Elf, and Half Orc
    1. Generates the following data
        - Randomly creates the stats for 6 characteristics
            - Characteristics: Strength, Dexterity, Constitution, Intelligence, Wisdom, Charisma
            - Random generation is rolling 4 six-sided dice, and adding the highest 3 rolls
1. Display Current Character
    - Includes the following data:
        - Character Name
        - Player Name
        - Character Ancestry
        - Characteristics Stats (Strength, Dexterity, Constitution, Intelligence, Wisdom, Charisma)
1. Add Current Character to Party
    - Should add the last created character to the Party
    - Should redisplay the main menu
1. Display the Current Party
    - Includes all the data for a Current Character, but for every character in the party
    - Should redisplay the main menu
1. All screens should be visually pleasing and easy to read and navigate.
