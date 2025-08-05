# DDosMinecraftPY

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

![Minecraft Bot Tool](https://i.imgur.com/placeholder.png)

Minecraft Bot Tool v3 is a Python-based utility designed for stress testing Minecraft servers. This tool creates multiple virtual players (bots) that connect to a Minecraft server, send messages, and move around to simulate real player activity.

> **Disclaimer:** This tool is intended for educational and legitimate stress testing purposes only. Only use this tool on servers you own or have explicit permission to test. Unauthorized use of this tool to disrupt or overload servers may be illegal and could result in severe legal consequences. The author takes no responsibility for any misuse of this tool.

## Features

- Create multiple concurrent Minecraft bot connections
- Customizable bot names with random suffixes
- Message spamming with configurable intervals
- Bot movement simulation to prevent AFK kicks
- Server status verification before launching bots
- Graceful shutdown with Ctrl+C
- Keepalive packet handling to maintain connections

## Installation

1. Clone the repository:
```bash
git clone https://github.com/KilixKilik/DDosMinecraftPY.git
cd DDosMinecraftPY
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Make the script executable (optional):
```bash
chmod +x core.py
```

## Usage

1. Run the tool:
```bash
python core.py
```

2. Follow the interactive prompts:
   - Enter the target server IP address
   - Specify the port (default: 25565)
   - Set the number of bots to connect
   - Choose a base name for bots (e.g., "Bot")
   - Enter the message to spam
   - Set movement interval in seconds (default: 5)

3. Press Ctrl+C to stop all bots gracefully

## Requirements

- Python 3.6+
- mcstatus library
- Standard Python libraries (socket, threading, etc.)

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Important Note

This tool should only be used for:
- Testing your own Minecraft servers
- Authorized penetration testing with explicit written permission
- Educational purposes in controlled environments

Using this tool against servers without proper authorization is illegal and unethical. The developer is not responsible for any misuse of this tool.

---

*Created by KilixKilik | August 5, 2025*
