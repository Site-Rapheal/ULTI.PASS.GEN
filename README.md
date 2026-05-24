# ULTI.PASS.GEN
ULTI.PASS.GEN is an advanced, offline-first cryptographic tool that transforms simple memorable words into unbreakable, bank-grade passwords. Unlike standard password managers, it uses a unique reversible mathematical cipher. 
Zero-Knowledge Architecture: 100% serverless. The cryptography happens entirely in your local CPU. Your passwords and memorable words are never stored or transmitted.

5-Tier Security Levels: Scales from simple numeric codes to the "Ultimate" tier, which uses advanced positional scrambling (mixing uppercase, lowercase, numbers, and symbols) to create patternless strings.

Cryptographic PIN (Salting): A secret 2-to-4 digit PIN mathematically shifts the entire cipher. Even if a hacker knows your memorable word and has the tool, they cannot generate or reveal your password without your exact PIN.

Dynamic Padding (Junk Blocks): A length-extender that generates deterministic, random-looking "junk blocks" to hide the true length of your memorable word. The Reveal engine knows exactly how to slice these off to decode your word safely.

Smart Pass-Through: Intelligently recognizes intentional special characters (like hyphens or spaces) and preserves them perfectly through both the generation and reveal processes.

Premium Glassmorphism UI: Features an adaptive frosted-glass interface with live visual cipher breakdowns, a dynamic password strength meter, and ambient color-shifting backgrounds (Mint/Green for Generation, Violet/Purple for Reveal).
