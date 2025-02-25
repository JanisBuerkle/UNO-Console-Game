# 🃏 UNO WPF App with Multiplayer 🎲

Welcome to the **UNO WPF App**! This application brings the classic UNO card game to your Windows PC, featuring both online and local multiplayer modes. Developed using WPF and following the MVVM architecture, it offers an exciting and interactive gaming experience.

## 🌟 Key Features

- **Multiplayer Modes**:
  - **Local Mode**: Play with friends on a single device.
  - **Online Mode**: Create or join rooms to play with friends over the internet.

- **Game Rules**:
  - Up to 5 players can join a game, starting with 7 cards each.
  - Match cards by color or number, or play action cards to change the game flow.
  - First player to play all their cards wins!

- **Card Details**:
  - 108 cards total: blue, green, red, and yellow.
  - Special cards: Draw Two, Reverse, Skip, Wild, and Wild Draw Four.

## 🛠️ MVVM Architecture

- **Model**: Manages core game logic and data, including players and cards.
- **View**: Presents the game interface using XAML.
- **ViewModel**: Bridges the Model and View, handling interactions and updates.

## 🖥️ Main Menu Options

- **Local**: Add players, set names, and start a local game.
- **Multiplayer**: Create or join rooms, set passwords, and manage player settings.
- **Scoreboard**: View player rankings based on game wins.
- **Settings**: Toggle between fullscreen and windowed modes.
- **Exit**: Close the application.

## 📡 Multiplayer Architecture

- **Database**: Stores room and player data.
- **SignalR Hub**: Manages real-time player connections and game updates.

## 🎴 Card Details

- **Sample Cards**:
  - **Skip Blue**
  - **7 Red**

---

Enjoy the strategic and fast-paced world of UNO with the UNO WPF App! Whether playing locally or online, challenge your friends and aim for victory! 🚀
