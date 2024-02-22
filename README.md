# Minesweeperbot

Welcome to the Minesweeperbot project! This bot is designed to help you navigate through the classic game of Minesweeper, offering hints, strategies, and automatic gameplay. Our script is easy to use and can be loaded directly into any Minesweeper game webpage that supports JavaScript injection via the browser's developer console.

## Features

- **Auto-Solve:** Let the bot solve the Minesweeper game for you.
- **Hint System:** Get hints for your next move. (WIP)
- **Custom Strategies:** Apply different strategies for solving the game. (WIP)

## How to Use

Using the Minesweeperbot is simple and requires no installation. Follow these steps to get started:

1. **Open Minesweeper Game:** Go to your favorite Minesweeper game website in your web browser.

2. **Open Developer Console:** Press `F12` to open the Developer Tools of your browser. 

3. **Navigate to Console Tab:** Click on the "Console" tab within the Developer Tools. This is where you'll paste the script.

4. **Load the Bot:** Copy and paste the following line into the console and press Enter:

    ```javascript
    $('head').appendChild(document.createElement('script')).src='https://cdn.jsdelivr.net/gh/Tpanda03/Minesweeperbot@main/msbot.js';
    ```

    This line of code adds the Minesweeperbot script to the current page, enabling its features for use.


## Contributing

Contributions to the Minesweeperbot project are welcome! Whether you have suggestions for new features, improvements, or have found a bug, please feel free to open an issue or submit a pull request.


## Disclaimer

This bot is provided "as is", without warranty of any kind. Use it at your own risk. The creators are not responsible for any consequences that may arise from its use.

Enjoy your enhanced Minesweeper experience with Minesweeperbot!
