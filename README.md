📄 ✂️ Stone Paper Scissors – Simple Web Game

A lightweight and fun Stone–Paper–Scissors game built using HTML, CSS, and JavaScript.
The user selects one of three options (stone, paper, or scissor), and the computer randomly chooses its move. The final result is displayed using an alert popup.

🎮 Demo

The game interface features three clickable images representing:

Stone

Paper

Scissor

Clicking any option triggers the game logic, randomly generating the computer's move and showing the result.

📁 Project Structure
project-folder/
│
├── index.html
├── 1.png        (image for stone)
├── 2.png        (image for paper)
├── 3.png        (image for scissor)

🛠️ Technologies Used

HTML5 – Structure of the game

CSS3 – Basic styling

JavaScript – Game logic and random computer move generation

🚀 How to Run the Game

Download or clone this project:

git clone <repository-url>


Place the image files (1.png, 2.png, 3.png) in the same directory as index.html.

Open index.html in your browser.

Click any icon (stone, paper, or scissor) to start playing!

🧠 Game Logic

The computer generates a random number between 0 and 1 using:

Math.random();


Based on this value, the computer selects one of the three moves.

The game compares the player's choice with the computer's choice and shows:

✅ YOU WIN

❌ YOU LOSE

🔁 TIE

📸 Screenshots (Optional)

You may add game screenshots here after running the project.

📌 Future Improvements

Here are some ideas to improve the project:

Replace alerts with an on-screen result display

Add score tracking for user and computer

Add animations and sound effects

Improve responsive layout

Add dark mode

📄 License

This project is free to use and modify. No restrictions.
