# Johny

I used to build post-quantum P2P networks and TLS-intercepting security tools. Now I build the same kind of software for a lab bench instead of a network stack — and it turns out most biotech tooling has the same problem blockchain had: too much software that only runs on the author's laptop.

## What I'm doing

- Studying biotech/bioengineering, with prior hands-on lab experience in analytical methods.
- Writing native Rust tools for problems I've actually hit at the bench: FASTQ quality control, HPLC/mass-spec data parsing.
- Bringing a systems background into biotech: `cogitator` (TLS interception proxy) and `primus-project` (post-quantum P2P blockchain, ML-DSA-87 signatures, Noise_XX over QUIC) were the training ground. No unsafe code, no "works on my machine."

## Projects

- **[HPLC](#)** — parses HPLC/mass-spec instrument exports into one format, with automatic peak detection and visualization. Built after watching real lab data get mangled by inconsistent vendor exports.
- **[fastqc-rs](#)** — FASTQ quality control as a native binary. No Python environment, no dependency hell, just double-click and go for a wet-lab user.
- **[cogitator](#)** — terminal-based TLS MITM proxy and web security toolkit. Finished and scoped on purpose, not a work-in-progress.
- **[primus-project](#)** — post-quantum Layer-1 blockchain: ML-DSA-87 signatures, Noise_XX P2P over QUIC, Merkle-Patricia Trie state. Solo research project — where the systems background comes from.

## Stack

Rust · systems programming · applied bioinformatics tooling

---

Open to hearing from research groups, internships, or collaborators working at the intersection of software and wet-lab biology.
