---
layout: project
type: project
image: img/HangMan.png
title: "Hangman"
#All dates must be YYYY-MM-DD format!
date: 2024-02-14
published: true
labels:
  - game
  - hangman
  - C#
summary: "I developed a simple word guessing game based on the well known HangMan game.."
---

<div class="text-center p-4">
  <img width="200px" src="..img/HangMan.png" class="img-thumbnail" >
  <img width="200px" src="../img/HangMan.png" class="img-thumbnail" >
  <img width="200px" src="../img/HangMan.png" class="img-thumbnail" >
</div>

Hangman is a classic word-guessing game that has entertained players for generations. The game involves two players: the "word setter" and the "guesser." Here's how it works:

The **word setter** secretly chooses a word and displays a series of blank spaces, each representing a letter in the chosen word. For example, if the secret word is "APPLE," the display might look like "_ _ _ _ _."

The guesser begins by suggesting a letter. If the letter is part of the secret word, the word setter reveals its position(s) in the blanks. If not, the guesser loses a life (often represented by drawing parts of a stick figure on a gallows).

The guesser continues to suggest letters until they either guess the entire word or run out of lives. The game typically limits the number of incorrect guesses allowed. If the guesser successfully guesses the word, they win; otherwise, the word setter wins.

Hangman can be customized with different themes (e.g., animals, countries, movies) and variations (e.g., using phrases instead of single words). It's a fun and challenging game that tests vocabulary, deduction skills, and a bit of luck!

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
