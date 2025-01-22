# Sentisify

# Overview

Sentisify is a Python-based sentence completion tool that predicts the next word based on user input and a predefined dataset. By analyzing word patterns, it suggests the most probable next words, providing users with an enhanced writing experience.

# Features

1.  Word Prediction:

Real-time suggestions for the next word based on the current context.

Uses a predefined dataset to calculate probabilities of next-word predictions.

2.  Interactive Interface:

Command-line interface with real-time word completions.

Displays the top 5 most probable next words.

3.  Custom Commands:

//exit: Exit the application.

//clear: Reset the current sentence.

4.  Offline Functionality:

Fully operational without the need for internet access.

# How It Works

1.  Dataset Loading:

Reads words from data.txt, processes them, and removes duplicates.

2.  Word Frequency Calculation:

Calculates the frequency of words following the user's input.

Computes probabilities for the next words based on frequency.

3.  Real-time Suggestions:

Displays the top 5 probable next words sorted by their probabilities.

4.  Sentence Building:

Users can iteratively build a sentence by selecting or typing the next word.

# Future Improvements

1.  Add support for phrase-level predictions.

2.  Optimize word frequency calculation for larger datasets.

3.  Enhance the CLI with additional customization options.

4.  Implement a graphical user interface (GUI).
