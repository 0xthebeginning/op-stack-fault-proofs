## ⚙️ OP Stack Fault Proofs

### ✅ What I'm Studying

- [`op-program`](https://github.com/ethereum-optimism/optimism/tree/develop/op-program)  
  Core logic for generating and verifying execution traces between L2 and L1. Written in Go.

- [Fault Proof Specification](https://github.com/ethereum-optimism/specs/blob/main/specs/fault-proof/index.md)  
  Detailed specification of how OP Stack handles fault proofs—including dispute games and correctness verification.

- [`op-dispute-mon`](https://github.com/ethereum-optimism/optimism/tree/develop/op-dispute-mon)  
  Monitors and verifies correctness of fault proofs on-chain. Useful for understanding proof submission.

### 📚 What I'm Trying to Understand

- How L2 execution traces are reproduced and verified on L1  
- How the `op-program` reads inputs and produces outputs  
- The role of `op-dispute-mon` in validating and submitting results
