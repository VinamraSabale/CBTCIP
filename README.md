# MasterMind Game

his code is for a simple game called "Mastermind" where there are two players. One player is a computer (Player 1), and the other player is a human (Player 2).

Here's how the game works:

1. You start the game by choosing a difficulty level (Easy, Moderate, or Hard) by entering 1, 2, or 3.

2. Depending on the difficulty level you choose:
   - Easy: You need to guess a four-digit number, and you have 5 attempts.
   - Moderate: You need to guess a five-digit number, and you have 8 attempts.
   - Hard: You need to guess a six-digit number, and you have 11 attempts.

3. The computer (Player 1) randomly generates a multi-digit number that you need to guess. The computer keeps this number a secret.

4. Your goal (Player 2) is to guess the computer's secret number within the given number of attempts.

5. You enter your guess, making sure it has the same number of digits as required for your chosen difficulty level. If your guess doesn't have the right number of digits, you're disqualified from the game.

6. After each guess you make, the game provides you with feedback:
   - If some of the digits in your guess are correct and in the correct position, you'll see those digits displayed as "X."
   - If some digits are correct but in the wrong position, you'll see how many of them are right, but not where they are.
   - If none of the digits are correct, you'll be told that none match.

7. You continue guessing until you either:
   - Guess the entire number correctly in one attempt and win the game.
   - Use up all your attempts, in which case the game is over, and the computer reveals the secret number.

8. The game keeps track of how many attempts you've made, and if you win, it tells you how many attempts it took you to guess the number.

9. The game also ensures that you follow the rules, and if you enter a guess with the wrong number of digits, you'll be disqualified.

10. The game ends when you either win by correctly guessing the number or lose by running out of attempts.
