## Hi there, my name is Cremero 👋

🛰️ Featured project: Skynet

My personal homelab. It started as a simple Minecraft server to play with friends and grew into my real-world testbed for everything I'm learning — and the backbone of my final-year project.

→ Check out the repo: https://github.com/Cremero/Skynet

Everything runs on Docker over Ubuntu Server, with configuration version-controlled in Git:

🎮 Crafty Controller — Minecraft server management (where it all started)
🎬 Jellyfin — self-hosted media streaming
🛡️ AdGuard Home — DNS with ad blocking + DNS over TLS
🔒 Tailscale — remote access without opening ports
⚙️ n8n + Ollama — automations powered by local LLMs
☁️ Cloudflare Tunnel — controlled service exposure

What I'm most proud of: a real incident with CrowdSec that locked me out of the server entirely, even over VPN. Instead of panicking and ripping things out at random, I diagnosed it step by step until I isolated the root cause (a firewall rule that was also blocking the Tailscale interface) and documented the whole process. That's the part of the project I value most — not the service itself, but how I solved it.

🧰 Tools I work with

Linux · Docker · Git · Networking (DNS, VPN, firewalls) · Bash · n8n

📫 Contact

[your email] · [your LinkedIn]
