# Band-Name-Generator
name = input("\nWelcome to the Band Name Generator.\n\nWhat is your name?\n")
fav_activity = input("\nWhat's your favorite activity to do in the summer? (cannot end in -ing)\n")
city = input("\nWhat's the name of the city you grew up in?\n")
adjective = input("\nWhat's an adjective you would use to describe your favorite flavor of ice cream? (Taste, color or texture)\n")
band_name = (name) + " and the " + (adjective) + " " + (fav_activity) + "ers of " + (city)
print("\nYour band name could be " + (band_name) + "!\nWhat do you think about that, " + (name) + "?")
