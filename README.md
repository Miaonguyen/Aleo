Leo is a functional, statically-typed programming language built for writing private applications.
Table of Contents
🍎 Overview
⚙️️ Build Guide
🦀 Install Rust
🐙 Build from Source Code
🦁 Update from Leo
📦 Download using Cargo
🚀 Quick Start
🧰 Troubleshooting
📖 Documentation
🤝 Contributing
❤️ Contributors
🛡️ License
🍎 Overview
Welcome to the Leo programming language.

Leo provides a high-level language that abstracts low-level cryptographic concepts and makes it easy to integrate private applications into your stack. Leo compiles to circuits making zero-knowledge proofs practical.

The syntax of Leo is influenced by traditional programming languages like JavaScript, Scala, and Rust, with a strong emphasis on readability and ease-of-use. Leo offers developers with tools to sanity check circuits including unit tests, integration tests, and console functions.

Leo is one part of a greater ecosystem for building private applications on Aleo. The language is currently in an alpha stage and is subject to breaking changes.

⚙️️ Build Guide
🦀 Install Rust
We recommend installing Rust using rustup. You can install rustup as follows:

macOS or Linux:

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
Windows (64-bit):

Download the Windows 64-bit executable and follow the on-screen instructions.

Windows (32-bit):

Download the Windows 32-bit executable and follow the on-screen instructions.

🐙 Build from Source Code
We recommend installing Leo by building from the source code as follows:

# Download the source code
git clone https://github.com/AleoHQ/leo
cd leo

# Install 'leo'
$ cargo install --path .
Now to use leo, in your terminal, run:

leo
🦁 Update from Leo
You can update Leo to the latest version using the following command:

leo update
Now to check the version of leo, in your terminal, run:

leo --version
📦 Download using Cargo
You can also install Leo directly from crates.io using cargo:

cargo install leo-lang
Now to use leo, in your terminal, run:

leo
🚀 Quick Start
Use the Leo CLI to create a new project

# create a new `hello-world` Leo project
leo new helloworld
cd helloworld

# build & setup & prove & verify
leo run main 0u32 1u32
The leo new command creates a new Leo project with a given name.

The leo run command will compile the program into Aleo instructions and run it.

Congratulations! You've just run your first Leo program.

🧰 Troubleshooting
If you are having trouble installing and using Leo, please check out our guide.

If the issue still persists, please open an issue.

📖 Documentation
Hello World - Next Steps
Leo Language Documentation
Leo ABNF Grammar
Homepage
🤝 Contributing
Please see our guidelines in the developer documentation

❤️ Contributors
View all Leo contributors here.
