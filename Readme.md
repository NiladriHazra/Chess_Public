# ♟️ Crownix

**Crownix** is a web-based multiplayer chess application built using [Next.js](https://nextjs.org/). It offers a real-time, feature-rich online chess experience, complete with timers, game history, spectator mode, and customizable UI options.

---

## 🚀 Features

- 🔴 **Real-time Multiplayer** – Play with others using WebSockets
- 🏠 **Room-based Gameplay** – Unique room IDs for player matches
- ⏱ **Game Timer** – Adjustable chess clock
- 🔍 **Spectator Mode** – Watch ongoing games
- 📜 **Move History** – Display of moves in algebraic notation
- ♟ **Pawn Promotion** – Interactive promotion UI
- ✍️ **In-Game Chat** – Live messaging with emoji support
- ✋ **Draw Offers & Resignation** – Built-in game diplomacy options
- 📊 **Analysis Mode** – Review previous moves and positions
- 🎨 **Customization Options** – Multiple board and piece styles
- 📱 **Responsive Design** – Optimized for both desktop and mobile
- 🔊 **Sound Effects** – In-game audio cues
- ✨ **Animations** – Smooth UI transitions using Framer Motion

---

## 🛠️ Tech Stack

| Tech              | Purpose                                       |
|-------------------|-----------------------------------------------|
| **Next.js**       | React framework for server-side rendering     |
| **Socket.IO**     | Real-time communication between clients       |
| **Chess.js**      | Chess rules validation and game logic         |
| **React-chessboard** | Rendering the chessboard UI               |
| **Framer Motion** | UI animations                                 |
| **Howler.js**     | Audio effects                                 |
| **React-toastify**| Toast notifications                           |
| **emoji-picker-react** | Emoji support in chat                   |

---

## 🧩 Key Components

- **ChessBoard1.jsx / ChessBoard.jsx** – Core component handling:
  - Chessboard rendering
  - Move validation and game rules
  - Socket communication
  - Game state and timers

- **Modals & Sidebars** – Used for:
  - Game settings
  - Promotion selection
  - Game result messages

- **Custom Hooks** – For managing socket connections and timers

---

## 🧠 Game Logic Highlights

- **Move Validation**: Ensured using chess.js
- **Timer Control**: Countdown logic for both players
- **Endgame Detection**: Checkmate, stalemate, draw, resign
- **Captured Pieces**: Display of opponent and own captures
- **Pawn Promotion**: UI popup for promoting to Queen, Rook, Bishop, or Knight

---

## 🎨 UI Customization

Players can personalize their game experience:
- Choose board themes: *Classic*, *Wooden*, *Marble*, *Metal*
- Select piece styles: *Standard*, *Modern*, *Fantasy*
- Toggle:
  - Move highlights
  - Coordinates
  - Sound effects
  - Animations

---

# Chess_Public
