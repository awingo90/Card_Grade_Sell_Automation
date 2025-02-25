# Sports Card Management System

An automated system for capturing, processing, and analyzing sports cards across iPad and PC environments.

## Features

- Capture front/back images of cards with unique identifiers
- Estimate card grades during capture
- Process and enhance images automatically
- Extract card details using OCR and image search
- Analyze pricing for optimal sell/grade decisions
- Generate eBay listings for ungraded sales
- Create PSA submission forms for cards worth grading

## Requirements

- Python 3.8+
- Tesseract OCR
- iPad with Pythonista 3 (for capture functionality)
- iCloud Drive (for synchronization)

## Quick Start

1. Clone this repository
2. Run `python setup.py install` to install dependencies
3. Configure your `config.json` file with API keys
4. Follow the [installation guide](docs/installation.md) for complete setup

## Documentation

- [Installation Guide](docs/installation.md)
- [iPad Setup](docs/ipad_setup.md)
- [PC Setup](docs/pc_setup.md)
- [User Guide](docs/user_guide.md)
- [Troubleshooting](docs/troubleshooting.md)

## Development Workflow

This repository follows a cross-device development workflow:
1. Create and modify code on iPad using Pythonista
2. Synchronize through iCloud Drive and GitHub
3. Continue development on PC
4. Document all changes in commit messages

## License

[MIT License](LICENSE)
