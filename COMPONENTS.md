Letter

What does the component need?
A function that handles click events
It needs to receive a word.

What is its responsibility?
When a letter is clicked, it compares that letter with the letters of the random word received.

What things change during the execution of the component?
If the letter is correct it will be painted in the position that matches the letter of the word received in the GuessLetters component.

GuessLetters

What does the component need?
It needs to receive a letter from the letter component.

What is your responsibility?
Display the number of letters required.

What things change during the execution of the component?
If the required letter matches a letter of the received word, paint that letter on the screen.
If it is completed, run the Result 'Alive' component.

Use letters

What does the component need?
You need to receive letters pressed in the letter component.

What is its responsibility?
Display the letters pressed and without repeating.

What things change during the execution of the component?
The letters are painted over.

HangMan

What does the component need?
It needs to receive the letters that do not match the letters of the required word.

What is your responsibility?
Paint one element of the figure in ascending order for each letter not matched.

What things change during the execution of the component?
If the entire figure is painted, the Result 'Dead' component is executed.

Result

What does the component need?
You need the HangMan or GuessLetters component to be complete.

What is your responsibility?
Execute a message: Alive or Dead.
What things change during the component execution?
The result of the game.

Translated with www.DeepL.com/Translator (free version)
