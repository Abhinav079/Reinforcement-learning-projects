# Reinforcement Learning Projects

This repository contains a collection of projects related to Reinforcement Learning (RL). Each project focuses on implementing and experimenting with various RL algorithms to solve different tasks. The projects are written in Python using popular RL libraries such as TensorFlow and PyTorch.

## Project List

1. **CartPole-v1 Solver**
   - Implementation of a simple Q-learning agent to solve the CartPole-v1 environment.
   - [Link to Project](./cartpole_solver)

2. **Deep Q-Network (DQN) for Atari Games**
   - Application of DQN to play Atari 2600 games.
   - Includes training code and pre-trained models for several games.
   - [Link to Project](./dqn_atari)

3. **Policy Gradient Methods**
   - Comparison of policy gradient methods (REINFORCE, PPO) on custom environments.
   - Visualization of learning curves and policy performance.
   - [Link to Project](./policy_gradient)

4. **Multi-Agent Deep Deterministic Policy Gradients (MADDPG)**
   - Implementation of MADDPG for cooperative multi-agent environments.
   - Tested on OpenAI's multi-agent particle environment.
   - [Link to Project](./maddpg)

## Requirements

- Python 3.x
- TensorFlow or PyTorch (depending on the project)
- Additional dependencies listed in each project's README

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/reinforcement-learning-projects.git
    cd reinforcement-learning-projects
    ```

2. Set up a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Navigate to a specific project directory (e.g., `cd cartpole_solver`) and follow the instructions in the project's README to run the code.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspiration and code snippets from [OpenAI](https://openai.com) and [DeepMind](https://deepmind.com).

Feel free to explore each project's directory for more detailed information and usage instructions.
