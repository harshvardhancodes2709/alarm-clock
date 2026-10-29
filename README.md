# alarm-clock
A simple Python alarm clock that counts down for a specified number of minutes and seconds, then plays an alarm sound when the timer reaches zero.

# Python Alarm Clock ⏰

A simple alarm clock built with Python that lets users set a timer in minutes and seconds. When the countdown finishes, it plays an alarm sound.

## Features

- Set a custom timer in minutes and seconds.
- Display the remaining time in a countdown format.
- Play an alarm sound when the timer reaches zero.
- Use ANSI escape sequences to clear and update the terminal display.

## Requirements

- Python 3
- `playsound3` library
- An `alarm.mp3` audio file

## Installation

1. Clone this repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <your-project-folder>
   ```

3. Install the required library:

   ```bash
   pip install playsound3
   ```

4. Place your `alarm.mp3` file in the project directory.

## Usage

Run the Python script:

```bash
python3 main.py
```

Enter the number of minutes and seconds you want to wait. The countdown will begin, and the alarm will play when the timer finishes.

## Technologies Used

- Python
- `time` module
- `playsound3` library
- ANSI escape sequences

## License

This project is open-source and available for learning and personal use.
