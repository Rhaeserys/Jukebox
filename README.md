# Jukebox
Jukebox
import random

# Create a list of songs.
songs = ["song1", "song2", "song3", "song4", "song5"]

# Ask the user to select a song.
user_input = input("Select a song: ")

# Play the selected song.
if user_input in songs:
    play_song(songs[user_input])
else:
    print("The song you selected is not available.")
