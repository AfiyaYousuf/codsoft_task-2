# codsoft_task-2

# Amour Health Assistant

This project demonstrates a simple conversational health assistant named Amour, which provides basic responses based on user inputs about health conditions using text-to-speech functionality.

## Features

1. **Text-to-Speech Initialization**: The TTS engine is initialized once to improve efficiency.
2. **Greeting and Farewell**: Amour can recognize basic greetings and farewells and respond appropriately.
3. **Symptom Inquiry**: Amour can ask follow-up questions or provide advice based on specific symptoms mentioned by the user.
4. **Default Response**: For any unrecognized inputs, Amour asks the user to rephrase the question.

## Usage

- **Initialization**: When the script starts, Amour introduces itself.
- **User Interaction**: The user can type inputs, and Amour will respond accordingly. If the input is a farewell, the loop terminates.
- **Symptom Response**: Amour recognizes keywords like "headache," "cough," and "stomach cramp," and provides specific advice for each symptom.

## Example Interaction

```
you: Hi
Amour: Hello! How are you feeling today?
you: I have a headache.
Amour: I'm sorry to hear that! Headaches can be really uncomfortable. Take rest and stay hydrated. It's important to consult with a healthcare professional.
you: Bye
Amour: Goodbye! Have a great day!
