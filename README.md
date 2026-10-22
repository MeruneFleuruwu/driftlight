# DRIFTLIGHT — Game Protocol Reverse Engineering Lab Pack

**Derive an undocumented UDP game protocol from raw packets — then build your own client.**

DRIFTLIGHT is a tiny multiplayer arena game written for one purpose: to be
reverse engineered. Five hands-on labs take you from a raw packet capture to
a from-scratch reimplementation of the client:

1. **Capture & Dissect** (free) — frame layout, opcode census, first Wireshark dissector
2. **The Checksum** — recover the CRC parameters from black-box data, forge a valid frame
3. **The Chat Is Not Encrypted, It's Keyed** — session-key obfuscation, proven from the wire
4. **Into the Binary** — the stripped client in Ghidra + Frida
5. **Become the Client** — reimplement the client in Python against the real server

🌐 Site: https://merunefleuruwu.github.io/driftlight/
