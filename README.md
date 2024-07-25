# SACopters

## Main Game

The main environment consists of controlling the drone to hit as many balloons as possible within a time limit, competing against AI drones.

### Implemented Algorithms

1. **Human**: Control of the propellers with the arrow keys.
2. **PID**: A controller in control theory that uses the error between the drone's position and the target position to output propeller thrusts.
3. **SAC**: A Reinforcement Learning agent that trained itself on multiple episodes of the game, testing different actions and learning from the rewards it gets.

## Usage

The games are available to try as a Python package.

### Prerequisites

Make sure you have Python installed on your computer.

### Installation and Running the Game

1. **Force Downgrade pip**

    ```bash
    python -m pip install pip==21
    ```

2. **Install the package with pip**

    ```bash
    pip install git+https://github.com/utkarsh-20-rajput/SACopters.git
    ```

3. **Run the game**

    If you want to run the balloon game:

    ```bash
    python -m quadai
    ```

    - Control your drone by tapping the arrow keys.
    - Reach as many balloons as you can within the time limit.

### Alternative Setup

A similar environment can be set up using Anaconda Navigator.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

## Contributing

If you want to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## Contact

If you have any questions or suggestions, feel free to open an issue or contact me directly at [utkarsh20rajput@gmail.com](mailto:utkarsh20rajput@gmail.com).

---
*This project is maintained by Utkarsh Rajput.*
