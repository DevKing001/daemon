# NetherNodes Daemon

## Overview
## Installation

1. Clone the repository: `git clone https://github.com/DevKing001/daemon`

2. Go to panel directory: `cd daemon`

3. Install some important things: `apt install zip -y && unzip daemon.zip && cd daemon`

4. Install dependencies: `npm install`

5. Configure NetherNodes Daemon
- Get your Panel's access key from the panel's config.json file and set it as 'remoteKey'. Do the same for the other way, set your NetherNodes Daemon access key and configure it on the Panel.

6. Start the Daemon: `node . # or use pm2 to keep it online`

## Configuration
Configuration settings can be adjusted in the `config.json` file. This includes the authentication key for API access.

## Usage
The daemon runs as a background service, interfacing with the NetherNodes Panel for operational commands and status updates. It is not typically interacted with directly by end-users.

## Contributing
Contributions to enhance the functionality or performance of the **NetherNodes Panel** are encouraged. Please submit pull requests for any enhancements.

## License
(c) 2025 Dev and contributors. This software is licensed under the MIT License.

## Credits
SRYDEN Skyport
Tyrex Labs
- Thanks ether, achul123, privt, hopingboyz
- Made by Dev
