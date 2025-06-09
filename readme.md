# 🐍 Snake AI Game

A classic Snake game controlled by an AI agent using **Deep Reinforcement Learning**.  
The project is written in **Python** with a **Pygame** interface and uses **PyTorch** to train the AI to play.

---

## 📂 Project Structure

| File           | Description                                               |
| -------------- | -------------------------------------------------------- |
| `snake_game.py`| Snake game environment using Pygame                      |
| `agent.py`     | AI agent utilizing deep Q-learning                       |
| `train.py`     | Training loop for AI interaction and learning            |

---

## ⚙️ System Requirements

- Python 3.x  
- [Pygame](https://www.pygame.org/news)  
- [NumPy](https://numpy.org/)  
- [PyTorch](https://pytorch.org/)

---

## 🚀 Quick Setup

1. **Clone** or download the project:

```bash
git clone https://github.com/yourusername/snake-ai.git
cd snake-ai
```

2. Create and activate a virtual environment (recommended):

```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On macOS/Linux
source venv/bin/activate
```

3. Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run and Train the AI

Start the AI training loop:

```bash
python train.py
```

The AI will start playing and learning to increase its score over each playthrough.

---

## 🛠️ Details of `snake_game.py`

- Manages the game logic and interface with Pygame  
- Handles snake movement, food spawning, and collision detection  
- Displays the score  
- Adjusts game speed via the `SPEED` variable

---

## 💡 Notes

- To safely exit the game, close the window or press ESC (if implemented in the logic).  
- Training may take time depending on your machine’s configuration.  
- You can use `matplotlib` together with `IPython.display` to visualize training progress (in Jupyter Notebook).

---

### Project Result

![demo](assets/demo.png)

---

## 📝 License

This project is provided "as is" for educational and research purposes only.
