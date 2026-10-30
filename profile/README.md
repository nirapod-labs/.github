<a href="https://nirapod.org">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nirapod-labs/.github/main/profile/assets/hero-dark.svg">
    <img alt="Nirapod Labs. The cryptography that secures the internet should be proved, not just reviewed." src="https://raw.githubusercontent.com/nirapod-labs/.github/main/profile/assets/hero-light.svg" width="100%">
  </picture>
</a>

<p align="center">
  <a href="https://nirapod.org"><b>nirapod.org</b></a>&ensp;·&ensp;
  <a href="https://nirapod.org/research/">Research</a>&ensp;·&ensp;
  <a href="https://nirapod.org/approach/">Approach</a>&ensp;·&ensp;
  <a href="https://nirapod.org/news/">News</a>&ensp;·&ensp;
  <a href="https://nirapod.org/people/">People</a>&ensp;·&ensp;
  <a href="https://nirapod.org/security/">Security</a>
</p>

**Nirapod Labs** is a research lab for high-assurance cryptography. We implement the standards that secure the internet and formally verify the code: right results, no secret-dependent timing and no memory errors, for every possible input. A machine checks every proof, so anyone can run the checker and get the same answer.

<a href="https://nirapod.org/approach/properties/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nirapod-labs/.github/main/profile/assets/prove-dark.svg">
    <img alt="What we prove. P1 functional correctness, P2 constant-time execution, P3 speculative constant-time, P4 memory safety, each for every possible input." src="https://raw.githubusercontent.com/nirapod-labs/.github/main/profile/assets/prove-light.svg" width="100%">
  </picture>
</a>

### Verified cryptography

| | |
|---|---|
| [**nirapod-sha2**](https://github.com/nirapod-labs/nirapod-sha2) | SHA-2 and HMAC for x86-64 and AArch64 in Jasmin, proved correct and memory safe in EasyCrypt, and checked constant-time and speculative constant-time |
| [**pasta-glv-proofs**](https://github.com/nirapod-labs/pasta-glv-proofs) | A machine-checked Lean 4 proof of the wNAF recoding and Straus ladder in the GLV scalar multiplication of `pasta_curves` |

### The toolchain

| | |
|---|---|
| [**toolchain**](https://github.com/nirapod-labs/toolchain) | The Jasmin and EasyCrypt toolchain our verified cryptography is built and proved with, prebuilt for Linux and macOS |
| [**jasmin**](https://github.com/nirapod-labs/jasmin) | Our fork of the Jasmin compiler, where each change is a branch with its own pull request upstream |
| [**jasmin-crypto-vscode**](https://github.com/nirapod-labs/jasmin-crypto-vscode) | Syntax highlighting and language support for Jasmin (`.jazz`) in VS Code |
| [**easycrypt-vscode**](https://github.com/nirapod-labs/easycrypt-vscode) | Syntax highlighting and language support for EasyCrypt (`.ec`, `.eca`) in VS Code |

### Developer tools

| | |
|---|---|
| [**simenclave**](https://github.com/nirapod-labs/simenclave) | A real hardware Secure Enclave for the iOS and watchOS Simulators |
| [**simble**](https://github.com/nirapod-labs/simble) | Real Bluetooth Low Energy for the iOS and watchOS Simulators |

### Get in touch

Questions about our work, or want to work with us: **hello@nirapod.org**.
Found a flaw in our code, proofs or website: **security@nirapod.org**, and see our [disclosure policy](https://nirapod.org/security/).

<a href="https://nirapod.org">
  <img alt="Our mission is to make formal verification the standard for the cryptography the world depends on." src="https://raw.githubusercontent.com/nirapod-labs/.github/main/profile/assets/footer.svg" width="100%">
</a>
