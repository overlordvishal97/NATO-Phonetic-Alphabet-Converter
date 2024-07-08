# NATO-Phonetic-Alphabet-Converter
This code converts a user-inputted word into its corresponding NATO phonetic alphabet code words. The NATO phonetic alphabet is a standardized system used to clearly communicate letters and numbers over radio and phone communications.

# Usage
Run the code in a Python environment.
Enter a word when prompted to do so.
The code will output a list of phonetic code words corresponding to each letter in the inputted word.

# Requirements
Python 3.x
pandas library
A CSV file named "nato_phonetic_alphabet.csv" containing the NATO phonetic alphabet

# How it Works
The code reads the CSV file containing the NATO phonetic alphabet and creates a dictionary from it. The user is then prompted to enter a word, and the code uses the dictionary to create a list of phonetic code words corresponding to each letter in the inputted word.

# Example Output
If the user enters the word "HELLO", the output might look like this:
['Hotel', 'Echo', 'Lima', 'Lima', 'Oscar']
