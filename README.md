# Quizzler

A simple true/false quiz application built with Flutter that tests your knowledge with fun facts and trivia questions.

## Features

- **Interactive Quiz**: True/False questions with immediate feedback
- **Score Tracking**: Visual score indicators (green checkmarks for correct, red X's for incorrect)
- **Question Navigation**: Automatic progression through quiz questions
- **Quiz Completion**: Alert dialog when quiz is finished with restart option
- **Responsive Design**: Clean, dark-themed UI that works across different screen sizes

## Screenshots

*Coming soon - Add screenshots of your app here*

## Getting Started

### Prerequisites

- Flutter SDK (3.9.0 or higher)
- Dart SDK
- Android Studio or VS Code with Flutter extensions
- Android emulator or physical device for testing

### Installation

1. Clone the repository:
```bash
git clone https://github.com/StarkUsman/QuizzlerApp.git
cd QuizzlerApp
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## Project Structure

```
lib/
├── main.dart          # Main app entry point and UI
├── question.dart      # Question model class
└── quiz_brain.dart    # Quiz logic and question management
```

## Dependencies

- **flutter**: Flutter SDK
- **cupertino_icons**: iOS-style icons
- **rflutter_alert**: Beautiful alert dialogs

## How to Play

1. Launch the app
2. Read each question carefully
3. Tap "True" or "False" based on your answer
4. Watch your score build up at the bottom of the screen
5. Complete all questions to see your final results
6. Tap "Restart" to play again

## Quiz Questions

The app includes 13 interesting trivia questions covering various topics including:
- Animal facts
- Historical trivia
- Scientific facts
- Fun miscellaneous knowledge

## Key Learning Concepts

This project demonstrates several important Flutter concepts:

- **StatefulWidget**: Managing app state and UI updates
- **Custom Classes**: Creating reusable `Question` and `QuizBrain` classes
- **List Management**: Handling collections of questions and UI elements
- **Conditional Logic**: Quiz progression and game completion detection
- **User Interaction**: Button handling and user input processing
- **Alert Dialogs**: Displaying completion messages and restart functionality

## Customization

### Adding New Questions

To add more questions, edit the `_questionBank` list in `quiz_brain.dart`:

```dart
Question('Your question text here', true), // or false
```

### Styling

The app uses a dark theme with:
- Background: `Colors.grey.shade900`
- True button: Green
- False button: Red
- Text: White

Modify colors in `main.dart` to customize the appearance.

## Development

### File Overview

- **main.dart**: Contains the main app widget, quiz page UI, and user interaction logic
- **question.dart**: Simple model class for storing question text and correct answer
- **quiz_brain.dart**: Manages quiz state, question progression, and completion detection

### TODO Items

- [ ] Add more diverse question categories
- [ ] Implement difficulty levels
- [ ] Add sound effects
- [ ] Create a high score system
- [ ] Add question explanations

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is part of a Flutter learning challenge. Feel free to use it for educational purposes.

## Acknowledgments

- Flutter team for the amazing framework
- The Flutter community for helpful resources and inspiration
- Question content sourced from various trivia collections

---

**Built with ❤️ and Flutter**
