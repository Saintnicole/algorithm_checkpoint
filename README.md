Sentence Reader Algorithm

The Sentence Reader algorithm is designed to analyze a user-inputted sentence and calculate key statistics about it, including the number of words, the total length (characters), and the number of vowels. The program processes each character individually until it reaches a period (.), which marks the end of the sentence.

🔍 How It Works

The algorithm starts by reading a sentence input from the user.

It then initializes three counters:

los → keeps track of the length of the sentence (number of characters).

now → counts the number of words, assuming that words are separated by a single space.

nov → counts the number of vowels (a, e, i, o, u).

The algorithm uses a WHILE loop to go through each character in the sentence until it reaches the period (.).

Inside the loop:

When a space (" ") is detected, the word counter (now) increases by one.

When a vowel is detected, the vowel counter (nov) increases by one.

After processing each character, the length counter (los) increases by one.

Once the period is reached, the loop ends, and the total length (los) is incremented by one to include the period character.

🧮 Final Output

At the end of execution, the program displays:

The number of words in the sentence.

The total length of the sentence, including the period.

The number of vowels found in the sentence.

⚙️ Key Notes

Each character in the sentence is treated separately.

Words are assumed to be separated by a single space.

The last character must be a period (.) for the loop to stop correctly.
