WPAI
Wolf Packet AI

The intelligent, field-portable network diagnostic instrument for professionals.

Wolf Packet AI transforms network troubleshooting by synthesizing a comprehensive suite of diagnostic tools (L1-L7, wired & wireless) with the power of on-board AI analysis into a single, rugged, handheld Kiosk. Built upon a "crystal clear," non-offensive philosophy and a local-first architecture, it provides one-tap answers, clear deductions, and automated reporting without cloud dependencies.

Core Features:

All-Layer Triage: From physical cable fault TDR (ethtool) and PoE interrogation to L7 application health (curl).

Advanced Discovery: VLAN hopping, rogue DHCP detection, automated topology mapping (nmap, graphviz).

Performance Analysis: Intermittent fault logging (mtr), VoIP/QoS analysis (iperf3, tshark).

Hardware Integration: In-line tapping ("The Stalker" bridge), Wi-Fi/BLE scanning & locating ("The Watcher," "The Hound"), serial console access ("The Master Key").

On-Board AI: Local LLM (Ollama) provides summaries and deductions ("The Alpha's Lore").
Field Utilities: Note-taking, sketching, screenshot, optional webcam support, Bluetooth tethering for comms.

Secure & Robust: Read-Only OS (overlayfs), A/B Partitioning, Digitally Signed Updates.

Ecosystem: Integrates with stationary "Wolf Cub" sensor agents.

Tech Stack
Hardware: Orange Pi 5+/Raspberry Pi 5 (ARM64), ~10" Touchscreen, Dual NICs, Alfa Wi-Fi, GPS.

OS: Armbian / Raspberry Pi OS (Debian Bookworm base), Read-Only Root FS, A/B Partitions.

UI/Core: Python 3.11+ (Kivy or Flask/Chromium), Ollama.

Key Agents: nmap, tshark, kismet, mtr, iperf3, ethtool, bridge-utils, graphviz, and many other standard Linux utilities.

Status
In Development (Actively working towards MVP)

See the Roadmap for planned milestones.

License
MIT / GPLv3 (Final license TBD)

See the LICENSE file for full details once chosen.


