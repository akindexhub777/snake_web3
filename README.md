🐍 Snake Web3 – Snake on‑chain game.
A classic Snake game, but every round is recorded on the GenLayer blockchain the gameplay evolves dynamically.
**Smooth Snake gameplay** with progressive acceleration.

- **Wallet connection** (MetaMask / Rabby) on the **GenLayer Studionet** network.

- **GenLayer smart contract** written in Python – saves the final score in **a single transaction** (no spam).

- **Rewards system**: claim GEN tokens (testnet) if your score ≥ 5.

-  **Local leaderboard** and NFT badge unlocked at 10 points.

-  **Responsive design** with directional keys (keyboard + mobile D-pad).

##  How does it work?

1. The player connects their wallet (MetaMask) to the **GenLayer Studionet** network.

2. The player presses **Start** – a `start_game` transaction is sent, which generates a game theme using AI.

3. During the game, **no transactions are sent** (optimal fluidity).

4. At the end of the game (Game Over), a `submit_score(final_score)` transaction records the score on the blockchain.

5. The player can then claim a reward if their score is high enough.

6. Technologies used 

7. **Smart contract** | GenLayer (Python) – deployed on Studionet |

| **Frontend** | HTML5, CSS3, JavaScript (Vanilla) |

| **Web3** | Ethers.js + MetaMask / Rabby |

| **Hosting** | GitHub Pages
Online demo Local installation (for development)

