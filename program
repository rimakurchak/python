import time

def intro():
    print("Welcome to the Haunted House Adventure!")
    print("You find yourself in front of an old, spooky mansion on a dark and stormy night.")
    print("Do you dare to enter? (yes/no)")

def enter_house():
    print("\nYou enter the house and hear creaking floorboards.")
    print("You have two doors in front of you. One is to your left and the other to your right.")
    choice = input("Which door do you choose? (left/right): ").lower()
    if choice == "left":
        print("\nYou enter a dusty library filled with old books.")
        print("You find a key on one of the shelves.")
        print("What do you want to do? (take key/go back): ")
        choice = input().lower()
        if choice == "take key":
            print("You take the key and go back to the entrance.")
        elif choice == "go back":
            print("You go back to the entrance without the key.")
    elif choice == "right":
        print("\nYou enter a dimly lit dining room with a long, ornate table.")
        print("There's a feast set out, but it looks old and rotten.")
        print("What do you want to do? (eat/leave): ")
        choice = input().lower()
        if choice == "eat":
            print("\nAs you take a bite, you realize the food is cursed!")
            print("You feel your life force draining away.")
            print("Game Over!")
            return
        elif choice == "leave":
            print("You wisely decide to leave the dining room.")

    print("\nYou return to the entrance with the key in hand.")
    print("You now have the option to go upstairs (up) or check the basement (down).")
    choice = input("Where do you want to go? (up/down): ").lower()
    if choice == "up":
        print("\nYou go upstairs and find a locked door.")
        print("You use the key to unlock it.")
        print("Inside, you discover a treasure chest.")
        print("You've won the game! Congratulations!")
    elif choice == "down":
        print("\nYou cautiously descend into the dark basement.")
        print("You see a flickering light at the far end.")
        print("As you approach, you realize it's a ghost!")
        print("The ghost frightens you, and you flee in terror.")
        print("You return to the entrance.")

def main():
    intro()
    choice = input().lower()
    if choice == "yes":
        enter_house()
    elif choice == "no":
        print("You chicken out and run away.")
    else:
        print("Invalid choice. Please type 'yes' or 'no'.")

if __name__ == "__main__":
    main()
