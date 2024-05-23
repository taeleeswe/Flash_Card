# Flashy - A Language Learning Flashcard App

Flashy is a simple flashcard application built with Python and Tkinter. It helps users learn French vocabulary by showing a French word and allowing users to flip the card to see the English translation. Users can mark words they know, and these words will be removed from the learning list.

## Features
- **Random Flashcards**: Display French words randomly from the dataset.
- **Card Flip**: Automatically flips the card after a set time to reveal the English translation.
- **Track Learning Progress**: Removes known words from the dataset and saves the progress.

## How to Use
1. **Run the Application**: Execute the script to start the application.
2. **View a French Word**: A card with a French word is displayed.
3. **Flip the Card**: After 3 seconds, the card flips to show the English translation.
4. **Mark as Known**: Click the right button (with the checkmark) if you know the word. This removes the word from the learning list.
5. **Move to Next Card**: Click the left button (with the cross) to skip to the next card.

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/flashy.git
    ```
2. Navigate to the project directory:
    ```sh
    cd flashy
    ```
3. Install the required dependencies:
    ```sh
    pip install pandas tkinter
    ```
4. Run the application:
    ```sh
    python main.py
    ```
    
## Adding New Datasets
1. Create your dataset CSV file in the `data` directory.
2. Ensure the CSV file has two columns: one for the word or phrase in the original language (or topic) and one for the translation or explanation.
3. Name the CSV file appropriately (e.g., `korean_words.csv` for Korean to English, `historical_facts.csv` for historical facts).

![Screenshot 2024-05-23 at 10 14 27 AM](https://github.com/taeleeswe/Flash_Card/assets/123449246/ea1464ca-38c0-4d83-812f-f59dcb7ee289)
![Screenshot 2024-05-23 at 10 14 31 AM](https://github.com/taeleeswe/Flash_Card/assets/123449246/18772ce3-fad3-4182-a0eb-b484bdff854a)

