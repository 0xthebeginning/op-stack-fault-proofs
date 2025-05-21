# client/program.go

## Summary
This is the main entry point to the op-program client. It sets up the runtime, connects to preimage channels, and launches the proof execution pipeline.

## Key Concepts
- Uses L1/L2 preimage oracles for resolving claims
- Supports both interop and non-interop execution
- Logs success/failure of the claim verification

## Next Questions
- How do the preimage oracles fetch state?
- What happens inside RunPreInteropProgram?
- How does the claim get verified or rejected?
