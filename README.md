# Stopwatch-Timer-Java
A clean and modern Stopwatch & Countdown Timer desktop app built using pure Java Swing.
Includes a stylish UI, smooth navigation, and a customizable countdown timer.

✨ Features


⏱ Stopwatch: Start, Stop, Reset

⏳ Custom Timer: Enter hours, minutes, seconds

🔁 Reset asks for new time

🧭 Options page for navigation

🎨 Modern UI: Buttons, clean fonts, centered layout

💯 Pure Java (no external libraries)


🧠 Concepts Used


✔ Object-Oriented Programming:

Encapsulation:

Modular class structure.
Each screen has its own class (SRP).
WindowManager handles all navigation.
ModernTheme & ModernButton manage UI consistency.

✔ Event-Driven Programming

Uses javax.swing.Timer.
Timer runs independently on Swing’s Event Dispatch Thread (EDT).
Smooth UI updates without freezing.
Behaves like lightweight multithreading inside Swing.


🚀 How to Run

Using Terminal

javac package_name/*.java

java package_name.Main

Using IDE

Open the project → Run Main.java

🛠 Tech Stack

Java 8+

Swing (GUI Framework)
