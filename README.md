# Heading-Python-Program-for-a-Number-Guessing-Game-33-100
import random

target_num = random.randint(1, 10)
guess_num = 0

while target_num != guess_num:
    guess_num = int(input('Guess a number between 1 and 10 until you get it right: '))

print('Well guessed!')

Guess a number between 1 and 10 until you get it right: 3
Guess a number between 1 and 10 until you get it right: 7
Guess a number between 1 and 10 until you get it right: 5
Guess a number between 1 and 10 until you get it right: 1
Well guessed!


