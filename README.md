secret = 7

guess = int(input("Guess the number (1-10): "))

if guess == secret:
    print("🎉 Correct! You guessed it!")
elif guess > secret:
    print("Too high!")
else:
    print("Too low!")
