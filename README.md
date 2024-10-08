def start_adventure():
    print("Welcome to the dungeon!")
    choice1 = input("You see two doors. Do you go through the left door or the right door? (left/right): ")

    if choice1 == "left":
        print("You encounter a sleeping dragon. Do you sneak past it or attack it? (sneak/attack): ")
        choice2 = input()

        if choice2 == "sneak":
            print("You sneak past the dragon and find a treasure chest filled with gold. You win!")
        elif choice2 == "attack":
            print("The dragon wakes up and defeats you. Game over.")
        else:
            print("Invalid choice. Game over.")

    elif choice1 == "right":
        print("You fall into a pit of spikes. Game over.")
    else:
        print("Invalid choice. Game over.")

start_adventure()


<!---
alyzzaalonsabe/alyzzaalonsabe is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
