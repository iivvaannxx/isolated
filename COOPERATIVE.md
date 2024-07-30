<div align="center">
  <h1>🤝🏻 Cooperative</h1>
  <p></p>
</div>

In the cooperative version, players must play on the same screen. The game is designed to be played with two players, it is not possible to play alone. The goal of this version is to reach the end of the level by working together, as they will need to help each other to overcome obstacles. At the end of the level, players will need to confront each other in a final battle to determine the winner.

## 🛠️ How to Play

Go ahead and download the game from the [releases page](https://github.com/iivvaannxx/isolated/releases/tag/1.0.0) for your operating system. Then follow the instructions below.

### Windows

1. Download the `IsolatedCooperative_Windows.zip` file.
2. Extract the contents of the zip file on your preferred location.
3. Run the `Isolated.exe` file.

### Linux
1. Download the `IsolatedCooperative_Linux.zip` file from the releases page.
2. Extract the contents of the zip file on your preferred location.
3. Run the `Isolated` executable via the following commands:
```bash
# Ensure the file is executable.
chmod +x Isolated
./Isolated
```
After doing this you will be presented with the setup scene I mentioned before. Configure your input device and start playing!

> [!WARNING]
> There's a known bug where the game allows you to control both players with the same gamepad. If you select a gamepad as the input device for both players and it's the same, you will be moving both players at the same time, and the game will be unplayable. To avoid this, make sure to use different gamepads for each player. If you use a keyboard for both, don't worry, the controls will be different for each player (explained below).

## 🎮 Controls

The controls depend on the input device you choose and whether you are player 1 or player 2. Because you can play with either a keyboard or a gamepad, there are three possible configurations.

### Case 1: Gamepad for both players

Each gamepad works the same, assuming they are different (read the warning above). The controls are as follows:

<div align="center">

| Move (Left / Right) | Jump | Crouch | Shoot | Reload | Aim (Up / Down) |
|---------------------|------|--------|-------|--------|-----------------|
| Left Stick | South Button | East Button | Right Trigger | West Button | Right Stick |

</div>

> [!NOTE]
> For example, for a typical PlayStation controller, jump would be `X`, crouch would be `O`, shoot would be `R2`, and reload would be `Square`.

### Case 2: Keyboard for both players

![Controls](./.github/assets/controls.png)

This may look a bit confusing, but it's actually quite simple. The first player will always use the **blue** controls, and the second player will use the **green** or **purple** controls depending if the keyboard has a numpad or not.

<div align="center">

| Numpad | Player | Move (Left / Right) | Jump | Crouch | Shoot | Reload | Aim (Up / Down) |
| --- | --- | --- | --- | --- | --- | --- | --- |
| \*  | P1  | `A` / `D` Keys | `W` Key | `S` Key | `Q` Key | `E` Key | `R` / `F` Keys |
| ✅   | P2  | `4` / `6` Keys | `8` Key | `5` Key | `7` Key | `9` Key | `Up` / `Down` Keys |
| ❌   | P2  | `J` / `L` Keys | `I` Key | `K` Key | `O` Key | `U` Key | `Y` / `H` Keys |

</div>

### Case 3 (Mixed): Gamepad for one player and keyboard for the other

This case is very simple, one player will use the controls listed in the [first case](#case-1-gamepad-for-both-players), and the other player will use **always** the **first set of controls** listed in the [second case](#case-2-keyboard-for-both-players) (blue), regardless of the keyboard configuration.
