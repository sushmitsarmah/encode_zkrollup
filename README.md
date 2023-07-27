Zokrates commands to create proof

1. Compile the zokrates file

        zokrates compile -i root.zok

2. Run Setup

        zokrates setup

3. Compute the witness. everything after a are the inputs defined in the function.

        zokrates compute-witness -a 337 113569  --verbose

4. Generate the Proof

        zokrates generate-proof

5. Export the verifier to a solidity file

        zokrates export-verifier

6. Or Verify with Zokrates

        zokrates verify