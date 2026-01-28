END-TERM-2
This website is an interactive Tic Tac Toe game built using HTML, CSS, and JavaScript with key core concepts of DOM. It is a fully client-side web application that runs directly in the browser without any external libraries or frameworks. The website is designed to feel like a real game product, not just a basic assignment, with a clean UI, start screen, player personalization, and a persistent leaderboard. 🧭 Website Flow (How it Works) 1️⃣ Start Screen When the website loads, the user first sees a start screen. It contains: Game title A motivational quote A “Start Game” button This improves first impression and user flow. When the user clicks Start Game, the main game screen appears. 2️⃣ Game Screen Layout The game screen is divided into two sections:

Left (≈ 3/4 width):

Player name inputs

Tic Tac Toe board

Game status (turn, win, draw)

Restart button

Right (≈ 1/4 width):

Leaderboard (Top 5 players)

This layout keeps the game as the primary focus and the leaderboard as secondary information.

3️⃣ Player Names

Players can enter their names for Player X and Player O.

Names are stored using localStorage, so they remain even after refreshing the page.

The game status dynamically shows:

“Akhila’s turn”

“Rahul wins 🎉” instead of generic “Player X”.

4️⃣ Game Logic

The Tic Tac Toe board is represented using a JavaScript array of 9 elements.

Each cell corresponds to an index in the array.

When a cell is clicked:

The current player’s symbol (X or O) is placed

The array is updated

Win conditions are checked

Win Conditions:

Rows

Columns

Diagonals

If a winning pattern is matched:

The game stops

The winner is announced

The leaderboard is updated

If all cells are filled without a winner:

The game is declared a draw

5️⃣ Leaderboard System

The leaderboard stores player names and win counts.

Data is saved using localStorage, so it persists across sessions.

Players are:

Sorted by number of wins

Limited to Top 5 only for clean UI

The top three players are visually highlighted:

🥇 Gold

🥈 Silver

🥉 Bronze

This makes the leaderboard informative without cluttering the interface.

🎨 UI & Design Choices

Gradient backgrounds for modern look

Card-style layout for clarity

Hover and click animations for better user experience

Safe CSS effects that do not interfere with JavaScript logic

Responsive-friendly structure using Flexbox

The design ensures that CSS handles appearance while JavaScript handles behavior, following best practices.

🧠 Key Core Concepts Used 🧱 HTML (Structure)

Semantic elements

Data attributes (data-index)

Forms and input fields

Lists for leaderboard

🎨 CSS (Styling & Layout)

Flexbox for layout (3/4 – 1/4 structure)

CSS variables for theme consistency

Gradients, shadows, transitions

Hover and active effects

Visual hierarchy and spacing

⚙️ JavaScript (Logic & Interactivity)

DOM manipulation

Event listeners

Arrays for game state

Conditional logic

Functions for reusability

Dynamic UI updates

💾 localStorage (Persistence)

Stores:

Player names

Leaderboard data

Ensures data remains after page refresh

Demonstrates real-world client-side storage usage

🧩 Important Software Engineering Concepts

Separation of concerns (HTML / CSS / JS)

State management (game state, current player)

User experience (UX) design Clean and readable code Scalability (easy to add new features)
