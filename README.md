
<h1 align="center">AGDaemon</h1>
## Overview
AG Daemon is the daemon for the Draco Panel.

## Installation
1. Clone the repository:
`git clone https://github.com/Aru1234rgb/ag-daemon

2. go to panel directory:
`cd draco-daemon` 

3. Install dependencies:
`npm install`

4. Configure AG Daemon:
- Get your Panel's access key from the Hydra panel's config.json file and set it as 'remoteKey'. Do the same for the other way, set your DracoDaemon access key and configure it on the Panel.

4. Start the Daemon:
`node . # or use pm2 to keep it online`

## Configuration
Configuration settings can be adjusted in the `config.json` file. This includes the authentication key for API access.

## Usage
The daemon runs as a background service, interfacing with the Draco Panel for operational commands and status updates. It is not typically interacted with directly by end-users.

## Contributing
Contributions to enhance the functionality or performance of the Draco Daemon are encouraged. Please submit pull requests for any enhancements.

## License
(c) 2024 Aru1234rgb and hopingboyz contributors. This software is licensed under the MIT License.

## Credits  
- **Developed by**: Aru1234rgb
- **made by**: hopingboyz   
- **Powered by**:  Aru1234rgb
- **Special Thanks**: hopingboyz

