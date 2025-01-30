# Browser Use First

A web automation project that provides a user-friendly web interface for browser automation tasks.

## Features

- Web-based UI for browser automation
- Support for custom automation tasks
- Configurable agent settings
- Recording and trace capabilities
- Vision-based automation support

## Installation

1. Clone the repository:
```bash
git clone https://github.com/hasankocaman/browser-use-first.git
cd browser-use-first
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Run the web UI:
```bash
python web-ui/webui.py --ip 127.0.0.1 --port 7788
```

Parameters:
- `--ip`: IP address to bind to (default: 127.0.0.1)
- `--port`: Port to listen on (default: 7788)
- `--theme`: UI theme name (default: Ocean)

## Configuration

The application uses a configuration file to store settings. If no configuration file is found, default settings will be used.

## Project Structure

- `web-ui/`: Contains the main web interface code
- `tmp/`: Temporary files directory
  - `record_videos/`: Recorded automation sessions
  - `traces/`: Browser trace files
  - `agent_history/`: Agent execution history

## License

This project is licensed under the MIT License - see the LICENSE file for details.
