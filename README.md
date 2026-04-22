# GGU Classroom Sign Page

Self-contained EIP-712 signing page for the GradeGoUp classroom game on Sepolia.

Students open `sign.html`, connect MetaMask on Sepolia, sign a claim (with their name), and optionally sign a golden-token allocation. Output is copyable JSON that the instructor verifies with `verify.py` (in the main toolkit repo).

Hosted via GitHub Pages for a stable URL across classes.

- GGU contract: `0x56f01E82bA31F8F585C0dF3d1A67B7DF4F325a2f` (Sepolia)
- Chain: Sepolia (chainId 11155111)
- No analytics. ethers.js v6 from jsDelivr; MetaMask in-browser.
