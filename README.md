# Contributing to RustDesk

Thank you for your interest in contributing to RustDesk!

## Quick Start

1. **Fork and clone the repository:**
   ```bash
   git clone https://github.com/your-username/rustdesk.git
   cd rustdesk
   ```

2. **Install dependencies:**
   Ensure you have Rust and Cargo installed (Rust 1.70+ recommended).
   - On Ubuntu/Debian:
     ```bash
     sudo apt-get update
     sudo apt-get install -y libgtk-3-dev libxcb-render0-dev libxcb-shape0-dev libxcb-xfixes0-dev libspeechd-dev libasound2-dev libpulseaudio-dev
     ```

3. **Build and check:**
   ```bash
   cargo build --release
   cargo clippy --workspace --all-targets
   ```

4. **Run tests:**
   ```bash
   cargo test
   ```

## Pull Request Process

- Ensure code formatting passes `cargo fmt --check` before submitting.
- Verify that `cargo clippy` emits no new warnings.
- Provide a clear description of the issue or feature in your PR description.
- Keep commits focused and atomic.