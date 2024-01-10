# Habit Tracker

Welcome to the Habit Tracker project! This Streamlit app allows you to track your habits, set goals, and monitor your progress over time.

## Getting Started

To run this project locally, ensure you have [Streamlit](https://streamlit.io/) installed. You can install it using:

```bash
pip install streamlit
```

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/your-username/habit-tracker.git
cd habit-tracker
```

Run the Streamlit app:

```bash
streamlit run app.py
```

The app will open in your default web browser, and you can start tracking your habits right away.

## Features

### Create New Habit

- Click on the "Create New Habit" section in the sidebar.
- Enter the name of your new habit and click the "Add habit" button.
- Your new habit will be added to the tracker, and you can start setting goals for it.

### Delete Habit

- Click on the "Delete Habit" section in the sidebar.
- Select the habit you want to delete from the dropdown and click the "Delete habit" button.
- The selected habit will be removed from the tracker.

### Track Habit Progress

- The main section displays the overall progress of all your habits.
- Each habit is presented in a separate column with customizable goals and progress bars.
- Set the goal, select the frequency, and update the number of times you've completed the habit.
- The progress bar visually represents your achievement towards the set goal.

### Save Data

- Your habit data is automatically saved in the `data.json` file.
- No need to worry about losing your progress; it will be loaded the next time you run the app.

## Contributing

If you have any suggestions, bug reports, or improvements, feel free to open an issue or submit a pull request. Your contributions are highly appreciated.

Happy habit tracking! 🚀
