# 🚀 Ergonaut Airdrop

A space-themed command-line tool for distributing tokens to Ergo miners. Designed for community token airdrops with style.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)

## 🌟 Overview

Ergonaut Airdrop is a mission control center for token distribution on the Ergo blockchain. It provides a user-friendly interface for sending tokens to miners, complete with real-time progress tracking and space-themed visualizations.

### ✨ Features

- Interactive space-themed CLI interface
- Real-time transaction progress tracking
- Support for multiple token types
- Miner filtering based on hashrate
- Debug/simulation mode for testing
- Rich terminal visualizations
- Wallet balance monitoring
- Transaction confirmation system

## 🛸 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ergonaut-airdrop.git
cd ergonaut-airdrop

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## 🎯 Prerequisites

- Python 3.8 or higher
- An Ergo node with API access
- Sufficient ERG for transaction fees
- Tokens to distribute
- Access to miner statistics

## 🚀 Usage

Basic command structure:
```bash
python airdrop.py <token_name> <amount> [options]
```

### Example Commands

```bash
# Test run with debug mode
python airdrop.py ProxyToken 1.0 --debug

# Live distribution
python airdrop.py ProxyToken 1.0

# Distribution with minimum hashrate filter
python airdrop.py ProxyToken 1.0 --min-hashrate 100
```

## ⚙️ Configuration

Create a `config.json` file in the project root:

```json
{
    "node_url": "http://your.node:9053",
    "api_key": "your_api_key",
    "wallet_address": "your_wallet_address"
}
```

## 🎮 Interactive Controls

During the airdrop process:
- Press `Y` to confirm launch
- Press `N` to abort mission
- Mission automatically times out after 30 seconds of inactivity

## 🔐 Security

- Always run in debug mode first
- Verify recipient addresses before launch
- Keep your API keys secure
- Ensure sufficient ERG balance for fees
- Monitor node synchronization status

## 🛠️ Development

```bash
# Install development dependencies
pip install -r requirements-dev.txt

# Run tests
pytest

# Run linter
flake8
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the APACHE License - see the [LICENSE](LICENSE) file for details.

## 🌌 Credits

Built with love for the Ergo community by your fellow Ergonauts.

## 🆘 Support

- Open an issue for bug reports
- Join our [Discord](https://discord.gg/your-invite) for community support
- Check the [Wiki](https://github.com/yourusername/ergonaut-airdrop/wiki) for detailed documentation

---

Made with ❤️ by Ergonauts, for Ergonauts.