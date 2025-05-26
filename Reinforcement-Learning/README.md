### CartPole Q-Learning with Deep Neural Network built with:
- **Python** for core logic
- **TensorFlow / Keras** for Q-value approximation via a neural network
- **NumPy** for numeric operations
- **OpenAI Gym** for CartPole simulation environment
- **Replay Memory**, **Epsilon-Greedy Policy**, and **Custom Reward** for enhanced control

---

# Deep Q-Learning: Balancing a Pole on a Cart

This project applies a Deep Q-Network (DQN) to solve the classic CartPole balancing challenge using the OpenAI Gym environment. The agent learns to take actions that keep a pole balanced by interacting with the environment, learning from experience, and improving its policy over time.

### **Key Insights:**
- Implemented Q-Learning with a neural network instead of a Q-table.
- Introduced a **Replay Buffer** for stable learning and better sample efficiency.
- Adopted **adaptive exploration**: epsilon decays faster after good performance.
- Designed a **custom reward function** to encourage better pole balance and centrality.
- Experimented with various **network architectures** to improve convergence speed.

---

## Dependencies

```bash
pip install numpy gym tensorflow
```

---

## License
This project is licensed under the MIT License.
