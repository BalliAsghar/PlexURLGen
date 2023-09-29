# PlexURLGen - CLI for Plex Server

A CLI tool for Plex server interaction, including authentication, media downloads, and playlist management via the command line.

## Prerequisites

Before using DownPlex, make sure you have the following prerequisites installed on your system:

- Python 3
- `pip` package manager

## Installation

### macos users can also install using brew

```bash
brew tap BalliAsghar/apps
brew install plex --formula
```

### Manual Installation

1. Clone or download the plex script from this repository.

2. Open a terminal or command prompt and navigate to the directory where you saved the script.

3. Install the required dependencies by running the following command:

   ```bash
   pip install -r requirements.txt
   ```

4. Move the script to a directory that is in your system's PATH. For example, on macOS, you can move the script to `/usr/local/bin`:

   ```bash
   mv plex /usr/local/bin
   ```

## Usage

```bash
plex [Command]
```

- `auth`: Authenticate your Plex account. You will be prompted to enter your username and password.
- `download`: Download media from a Plex server. Provide a valid Plex URL as an argument.
- `playlist`: Browse and download media from playlists on your Plex server.
  - `--m3u`: save playlist as m3u file
- `signout`: Sign out of your Plex account.

## Notes

- PlexURLGen uses the [keyring](https://pypi.org/project/keyring) package to store your Plex credentials. If you are uncomfortable with this, do not use this tool.
