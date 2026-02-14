# JetCrab Ecosystem

<div align="center">
  <img src="https://raw.githubusercontent.com/JetCrabCollab/JetCrab/main/assets/logo.png" alt="JetCrab Logo" width="200" height="200">
  
  <h3>High-Octane JavaScript Ecosystem Powered by Rust</h3>
  
  <p>Reimagining the JavaScript runtime experience with performance, safety, and simplicity at its core.</p>
</div>

---

## 🌊 The Ecosystem Architecture

The JetCrabCollab organization builds a modern, high-performance toolchain for JavaScript developers. Our architecture is composed of three distinct pillars, mirroring the structure of modern JS environments (e.g., V8, Node, NPM).

| Pillar | Project | Description | Role |
| :--- | :--- | :--- | :--- |
| **The Engine** | **[Chitin](./chitin)** | The core execution library. Wraps Boa and provides the raw JS capability. Equivalent to **V8**. | 🧠 Brain |
| **The Runtime** | **[JetCrab](./JetCrab)** | The executable runtime environment. Adds file system, network, and process capabilities. Equivalent to **Node.js/Deno**. | 🏃 Body |
| **The Manager** | **[CPM](./cpm)** | The Crab Package Manager. Handles dependencies, scripts, and project initialization. Equivalent to **NPM/Yarn**. | 📦 Tools |

## 🦀 Why JetCrab?

- **Native Performance**: Built from the ground up in Rust.
- **Unified Tooling**: Seamlessly integrate Rust modules into your JS projects.
- **Safety First**: Leveraging Rust's memory safety for a more stable runtime.
- **Fast Startup**: Optimized for sub-10ms initialization.

## 🛠️ Getting Started

To build the entire ecosystem from source, ensure you have Rust installed and run:

```bash
cargo build --release
```

### Usage

1.  **Initialize a project**:
    ```bash
    cpm init my-project
    ```
2.  **Install dependencies**:
    ```bash
    cpm install
    ```
3.  **Run a script**:
    ```bash
    cpm run dev
    ```

## 🤝 Community & Support

- **Discord**: [Join our developer community](https://discord.gg/jetcrab)
- **Documentation**: [Official Docs](https://docs.jetcrab.dev)
- **Discussions**: Use the Discussions tab in each repository for questions.

---

<p align="center">
  <i>"Speed of light, safety of lead."</i> — Built with 🦀 by the JetCrab Team.
</p>
