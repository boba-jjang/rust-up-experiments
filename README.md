# 🧪 rust-up-experiments

**rust-up-experiments** contains **runnable Rust code** created while exploring and validating ideas documented in **`rust-up-knowledge`**.

This repository is intentionally code-first and experimental.

---

## 🎯 Purpose

This repo exists to:
- Try things out in real Rust code
- Observe compiler errors and behavior
- Validate mental models
- Explore ownership, borrowing, lifetimes, traits, and more

These are **experiments**, not polished examples.

---

## 🧠 Structure

Experiments are organized **by Rust Book chapter**, not by abstract topic.

Each chapter directory contains one or more **standalone Cargo projects**.

```bash
.
├── ch2-guessing-game/
│ ├── guessing-game/
│ ├── Cargo.toml
│ └── src/main.rs
├── ch3-common-concepts/
│ └── ...
├── ch4-ownership/
│ └── ...
└── README.md
```

---

## Conventions
- One concept per folder
- Folder name = concept name
- Each folder builds and runs independently

---

## ▶️ Running an Experiment

From the repo root:
```bash
cd ch2-guessing-game
cargo run
```

Other useful commands:
```bash
cargo check
cargo build
cargo test
```
---

## 📜 License

All original code in this repository is released under the MIT License.
