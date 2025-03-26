# MCP Client

A Python-based client application for interacting with the Master Control Program (MCP) system.

## Prerequisites

- Python 3.x
- uv (Python package installer and environment manager)
- Poetry (dependency management)

## Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd mcp-client
```

2. Set up the virtual environment:
```bash
uv venv
source .venv/bin/activate  # On Unix/MacOS
# or
.venv\Scripts\activate  # On Windows
```

3. Install dependencies:
```bash
uv pip install 
```

4. Configure environment variables:
Create a `.env` file in the root directory with your configuration:
```env
MCP_API_KEY=your_api_key_here
```

## Project Structure

```bash
mcp-client/
├── client.py # Main client implementation
├── pyproject.toml # Project dependencies and metadata
├── .env # Environment variables
└── .venv/ # Virtual environment
```

## Usage

The client can be imported and used in your Python code:

```python
from client import MCPClient

# Initialize the client
client = MCPClient()

# Use the client methods
# (Add specific usage examples based on your client.py implementation)
```

## Development

This project uses:
- `uv` for dependency management and virtual environments
- `poetry` for package management
- Environment variables for configuration

### Development Setup

1. Make sure you have uv installed:
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

## Configuration

The client can be configured using environment variables:
- `MCP_API_KEY`: Your API key for authentication
- (Add other configuration variables as needed)

## Contributing

1. Fork the repository
2. Create a new branch for your feature
3. Make your changes
4. Submit a pull request

## License

[Add your license information here]