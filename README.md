# Slot-machine
This repository consists of python code which can run casino like games. 

This code was writen in a Jupyter Notebook environment and hence might not work the best in IDEs due to the fact that it was built with multiple code blocks running in parallel. The code will still run but the user interface won't be as friendly.

## Disclaimer: 
**Gambling is addicting and a bad habit. With this repository I do not mean to support gambling in any way. This project was solely made to understand the math behing the working of these games and learn python.**

## Setup:
To run this code on your device locally you will need to have some libraries like:
1. `matplotlib.pyplot` for graphing the probabilities to study the math behind the working of the code
2. `matplotlib.patches` for visualising the user interface in a better way

## Model Limitations and Future Enhancements
This slot machine model provides a foundational understanding of game mechanics, probability, and basic visualization. However, like any simplified model, it has certain limitations and many opportunities for further development:

### Current Limitations:
*   **Static Configuration**: The `strip` (symbol probabilities) and payout rates are hardcoded, making the game non-dynamic.
*   **Basic Win Conditions**: Only matching three identical symbols results in a win. Real slot machines often have multiple paylines (horizontal, diagonal), wild symbols, and scatter pays.
*   **Simple User Interface**: The visualization is static and purely graphical, lacking interactivity beyond input prompts. There are no animations or complex visual effects.
*   **No Persistence**: Player balances and game history are not saved between sessions.
*   **Limited Error Handling**: While some input validation exists, a more robust system would handle unexpected inputs more gracefully.

### Ideas for Further Development:
*   **Dynamic Game Configuration**: Allow users to define custom `strip` values, symbol weights, or payout rates, perhaps loaded from a configuration file.
*   **Advanced Win Logic**: Implement multiple paylines (horizontal, diagonal, V-shapes), wild symbols (e.g., a 'W' symbol that can substitute for any number), and scatter symbols (which pay regardless of position).
*   **Bonus Features**: Introduce bonus rounds, free spins, or progressive jackpots.
*   **Graphical User Interface (GUI)**: Migrate the visualization and interaction to a more robust GUI framework like `Tkinter`, `Pygame`, `PyQt`, or even a web-based interface using `Streamlit` or `Flask` to create an interactive experience with animations.
*   **Sound Effects**: Add sound effects for spinning, wins, and losses to enhance immersion.
*   **User Accounts and Persistence**: Implement a simple database (e.g., using `sqlite3`) to save player balances, high scores, and game statistics.
*   **Detailed Analytics**: Expand the probability testing to run thousands or millions of simulated spins to get empirical probabilities and compare them against theoretical ones, providing deeper insights into game fairness and player return.
