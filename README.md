# CLI Audio Player (Java)

A simple, command-line based audio player built using the Java Sound API (`javax.sound.sampled`). 
It allows users to play, stop, and reset `.wav` audio files directly from the terminal.

## Features

* **Playback Controls:**
  * `P` : Play audio
  * `S` : Stop/Pause audio
  * `R` : Reset to the beginning
  * `Q` : Quit application
* **Modern Java Syntax:** Utilizes Java Switch Expressions for cleaner code logic.
* **Error Handling:** Manages unsupported file types and audio stream errors gracefully.

## Requirements

* **Java 15 or higher** (Required for Switch Expressions).
* **Audio Format:** Supports `.wav` files (Java Sound API standard).

## Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/ietkose/music-player.git
    ```

2.  **Setup Audio File:**
    * If you want to add your own sound:
        * Place your `.wav` file inside the folder named `assets`.
        * Note: The default code looks for a specific filename. You may need to rename your file or update the path in `App.java`.*

3.  **Compile the Code:**
    ```bash
    javac src/App.java -d bin
    ```

4.  **Run the Player:**
    ```bash
    java -cp bin App
    ```

## 👨‍💻 Tech Stack

* **Language:** Java
* **Library:** `javax.sound.sampled`
* **Concepts:** File I/O, Exception Handling, Streams.
