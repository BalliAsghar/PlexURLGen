# DownPlex - CLI for Plex Server

DownPlex is a command-line interface (CLI) script that allows you to interact with your Plex server. With DownPlex, you can authenticate, download media, and manage playlists directly from the command line.

## Prerequisites

Before using DownPlex, make sure you have the following prerequisites installed on your system:

- Python 3
- `pip` package manager

### macos users can also install using brew

```bash
brew tap BalliAsghar/apps
brew install plex --formula
```

## Installation

1. Clone or download the DownPlex script to your local machine.

2. Open a terminal or command prompt and navigate to the directory where you saved the script.

3. Install the required dependencies by running the following command:

## Usage

```bash
plex [Command]
```

- `auth`: Authenticate your Plex account. You will be prompted to enter your username and password.
- `download`: Download media from a Plex server. Provide a valid Plex URL as an argument.
- `playlist`: Browse and download media from playlists on your Plex server.
