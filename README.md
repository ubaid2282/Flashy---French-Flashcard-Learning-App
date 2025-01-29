# Flashy---French-Flashcard-Learning-App
Flashy - French Flashcard Learning App
# Flashy - French Flashcard Learning App

## Overview
Flashy is a simple yet effective flashcard-based language learning application built using Python and Tkinter. This app helps users learn French vocabulary by displaying words in French and allowing them to flip the card to reveal the English translation. Users can mark words they have learned, and the app will save their progress.

## Features
- Displays French words and their English translations.
- Automatically flips the card after 3 seconds.
- Allows users to mark words as known.
- Saves progress by removing known words from future practice sessions.
- Uses a CSV file to store the words to learn.

## Technologies Used
- Python
- Tkinter (GUI development)
- Pandas (data handling)
- Random (random word selection)

## Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flashy.git
   cd flashy
   ```

2. Install dependencies:
   ```bash
   pip install pandas
   ```

3. Ensure you have the required directory structure:
   ```
   flashy/
   |-- data/
   |   |-- french_words.csv  # Contains the words to learn
   |   |-- words_to_learn.csv  # Stores user progress (auto-generated)
   |-- images/
   |   |-- card_front.png  # Flashcard front image
   |   |-- card_back.png  # Flashcard back image
   |   |-- right.png  # Right button image
   |   |-- wrong.png  # Wrong button image
   |-- main.py  # Main application script
   ```

4. Run the application:
   ```bash
   python main.py
   ```

## How to Use
- The app will display a French word.
- After 3 seconds, the card flips to show the English translation.
- Click the ✅ button if you know the word (removes it from the list).
- Click the ❌ button if you don’t know the word (keeps it for future practice).

