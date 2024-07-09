# PYTHON-
Create a program that stimulates rolling a dice
      ///        ///      ///      ///        ///
 import random

def roll_dice():
    return random.randint(1, 6)
def main():
    print("Welcome to the Dice Rolling Simulator!")
    while True:
        input("Press Enter to roll the dice...")
        result = roll_dice()
        print(f"You rolled: {result}")
        play_again = input("Roll again? (y/n): ").strip().lower()
        if play_again != 'y':
            print("Thanks for playing!")
            break
if __name__ == "__main__":
    main()
