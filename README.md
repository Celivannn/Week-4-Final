# Flash Card Study App

This Python project is a Flash Card Study App designed to help users create, organize, and study flashcards interactively. It allows for folder management, flashcard creation, and engaging study sessions. The application also supports dynamic theme customization to personalize the user experience.

## Features

### Flashcard Management
- Create folders to organize flashcards.
- Add flashcards with a question and answer to any folder.
- Delete folders or specific flashcards.

### Study Sessions
- Start a study session for a selected folder.
- Randomized flashcard order to test memory effectively.
- Receive feedback on answers (correct/incorrect) with a final score and mastery percentage.

### Theme Customization
- Change the app's theme dynamically using the built-in color picker.
- Updates background and button colors for a personalized experience.


## Usage

### Launching the App
Run `app.py` to open the Flash Card Study App. The app's graphical user interface (GUI) will launch, allowing you to interact with its features.

### Workflow
1. **Create Folders**:
   - Use the "Add Folder" button to create new folders for organizing your flashcards.

2. **Add Flashcards**:
   - Select a folder and use the "Add Flashcard" button to input questions and answers.

3. **Study Sessions**:
   - Select a folder and click "Start Study Session" to begin.
   - Answer questions interactively and receive real-time feedback.

4. **Customize Theme**:
   - Click "Change Theme" to open the color picker and choose a new background color for the app.

### Example
- Create a folder named "Science."
- Add flashcards:
  - Q: "What is the boiling point of water?" A: "100°C."
  - Q: "What is the chemical symbol for water?" A: "H2O."
- Start a study session to test your knowledge.

## Code Organization

```plaintext
flashcard_study_app/
|
├── flashcard_study_app/
│   ├── __init__.py         # Marks the folder as a Python package
│   ├── flashcard.py        # FlashCard class logic
│   ├── folder_manager.py   # FolderManager class logic
│   ├── ui.py               # User interface and theme customization
|
├── app.py                  # Main application entry point
├── README.md               # Documentation
```

### Key Components
1. **`flashcard.py`**: Defines the `FlashCard` class for storing question-answer pairs.
2. **`folder_manager.py`**: Manages folders and their associated flashcards.
3. **`ui.py`**: Implements the graphical user interface and theme management.
4. **`app.py`**: Initializes the application and demonstrates its functionality.


## Acknowledgments

Special thanks to the Python and Tkinter communities for their comprehensive libraries and documentation.And also to the members of this group by sharing their knowledge and insights on making this project successful.


