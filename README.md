# Bulls and Cows (Rust CLI)

A simple CLI-based guessing game built in Rust as part of the **HackQuest** Web3 learning track.

This project demonstrates core Rust fundamentals, focusing on interactive terminal input, random number generation, and pattern matching for state flow.

---

## 💡 Concepts Covered

During the development of this project, several key Rust concepts and standard library utilities were implemented:

- **CLI Input & Output (`std::io`)**: Capturing user input from the command line using `io::stdin().read_line()`.
- **String Parsing & Error Handling (`match`)**: Cleaning input with `.trim()`, parsing string slices into numbers with `.parse()`, and gracefully handling invalid entries using `match` statements.
- **Random Number Generation (`rand` crate)**: Generating pseudo-random integers within a bounded range (`1..11`) using thread-local random number generators.
- **Numerical Comparison (`std::cmp::Ordering`)**: Comparing values using `cmp()` and handling `Less`, `Greater`, and `Equal` variants to drive loop termination and game logic.
- **Variable Shadowing & Loops**: Re-using variable names cleanly while updating state within a continuous `loop` block.

---

## 🛠️ Prerequisites

Ensure you have Rust and Cargo installed on your system.

```bash
rustc --version
cargo --version
```

If you don't have Rust installed, set it up via [rustup.rs](https://rustup.rs/).

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/7orvx/bulls_and_cows.git
   cd bulls_and_cows
   ```

2. **Build and run the project:**
   ```bash
   cargo run
   ```

3. **Play the game:**
   - Enter a number between `1` and `10`.
   - Follow the terminal feedback (`too small!`, `too big!`) to guess the secret number within 10 attempts.

---

## 📜 License

This project is created for educational purposes following the HackQuest Web3 developer path.