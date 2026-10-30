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

### What we prove

- **Functional correctness.** The code computes exactly the result the standard defines.
- **Constant-time execution.** Secret values never shape the path the code takes or the memory it touches.
- **Speculative constant-time.** Secrets stay hidden even while the processor speculates past a wrong guess.
- **Memory safety.** Every read and write stays inside memory the code may use.

Each one holds for every possible input. [How we prove them](https://nirapod.org/approach/properties/)

### Verified cryptography

- [**nirapod-sha2**](https://github.com/nirapod-labs/nirapod-sha2): formally verified SHA-2 and HMAC in Jasmin, proved correct and memory safe in EasyCrypt, and checked constant-time and speculative constant-time.
- [**pasta-glv-proofs**](https://github.com/nirapod-labs/pasta-glv-proofs): machine-checked Lean 4 proofs of the wNAF recoding and Straus ladder in the GLV scalar multiplication of `pasta_curves`.

### Get in touch

Questions about our work, or want to work with us: **hello@nirapod.org**.
Found a flaw in our code, proofs or website: **security@nirapod.org**, and see our [disclosure policy](https://nirapod.org/security/).
