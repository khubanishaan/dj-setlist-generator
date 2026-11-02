# DJ Setlist Generator

A Java-based command-line application that helps DJs organize songs into one continuous setlist based on BPM and genre compatibility.

## The Problem

As someone interested in DJing and music, I find that organizing songs into a setlist can be time-consuming, especially when trying to create smooth transitions between different BPMs and genres. Manually deciding which songs work well together can be frustrating, particularly when working with a large collection of music.

## Project Goal

The goal of this project is to develop a tool that automatically arranges songs into a recommended playing order based on BPM differences and genre similarity, making DJ setlist planning easier.

## MVP Features

- Manually enter songs with their title, artist, BPM, and genre.
- Store entered songs in an ArrayList during the current session.
- Generate one continuous setlist using a BPM and genre compatibility algorithm.
- Display the generated setlist in the terminal.
- Save the generated setlist to a text file.

## How It Works

When the program starts, the user begins with an empty song collection. They can add songs through a command-line menu and generate a setlist once songs have been entered. The program calculates compatibility based on BPM differences and genres, then arranges the songs into a recommended order. The user can save the resulting setlist as a text file.

## Tech Stack

- **Language:** Java
- **Libraries:** Java standard library, including Scanner, ArrayList, Comparator, FileWriter, and BufferedWriter
- **Data Storage:** ArrayList for temporary song storage and a .txt file for exported setlists
- **User Interface:** Command-line interface (CLI)
- **Development Tools:** IntelliJ IDEA, Git, and GitHub
- **External APIs:** None

## Future Plans

- Import song collections from CSV files.
- Add musical key and energy levels to improve transition recommendations.
- Export generated setlists as CSV files.
- Allow users to manually rearrange generated setlists.
- Develop a web interface using Java, Spring Boot, HTML, and CSS.

## Project Documentation

- [Eisenhower Matrix](docs/eisenhower-matrix.pdf)
- [System Flowchart](docs/system-flowchart.png)

## Development Status

Planning stage. Implementation will follow the chunked milestones outlined in HW9.

## Author

Purdue University CS 193 Final Project - SHAAN KHUBANI.
