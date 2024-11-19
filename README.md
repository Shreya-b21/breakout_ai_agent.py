# Advanced Q-Learning Breakout AI Agent

This project implements an advanced Q-Learning agent for a Breakout-style game using Python. The agent uses reinforcement learning techniques to learn how to play the game effectively.

## Features

- Q-Learning algorithm with softmax action selection
- Decaying epsilon-greedy exploration strategy
- Decaying learning rate
- Advanced state representation including ball position, velocity, paddle position, and relative positioning
- Customizable reward function

## Requirements

- Python 3.7+
- NumPy
- Random
- Math

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/advanced-q-learning-breakout-ai.git
   ```
2. Navigate to the project directory:
   ```
   cd advanced-q-learning-breakout-ai
   ```
3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

Run the main script to train and test the AI agent:

```
python advanced_q_learning_breakout_ai_agent.py
```

The script will output training progress every 10,000 episodes and display final Q-table statistics and test results.

## Customization

You can modify the following parameters in the script to experiment with different configurations:

- `epsilon_start`, `epsilon_end`, `epsilon_decay`: Control the exploration-exploitation trade-off
- `learning_rate`, `min_learning_rate`, `learning_rate_decay`: Adjust the learning rate behavior
- `discount_factor`: Modify the importance of future rewards
- `temperature`: Adjust the softmax temperature for action selection

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](https://github.com/yourusername/advanced-q-learning-breakout-ai/issues) if you want to contribute.

## Author

[Your Name]

## Acknowledgments

- This project was inspired by the classic Breakout game and reinforcement learning techniques.
- Special thanks to the open-source community for providing valuable resources on Q-learning and AI in gaming.
