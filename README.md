# <center>File Share (fshare)</center>

<p align="center">
    <strong>FShare</strong> is a command-line utility for file sharing. It automatically copies the upload URL to your clipboard for easy sharing. You can set a deletion period for the uploaded file (default is 24 hours) or delete it immediately.
</p>

<p align="center">
    <img src="./demo.gif" alt="Demo GIF" />
</p>


## Features

- Automatically deletes uploaded files.
- Supports both Wayland and Xorg environments.
- Copies URL to clipboard for effortless sharing.
- Maintains history in `~/.fshare` for easy file management.

## Prerequisites

- **curl**: For HTTP requests.
- **fzf** (optional): For interactive file selection.
- **xclip** (optional): For Xorg clipboard support.
- **wl-clipboard** (optional): For Wayland clipboard support.

## Installation

1. Download the script:

   ```bash
   wget https://raw.githubusercontent.com/flarexes/fshare/main/fshare
   ```

2. Make the script executable:

   ```bash
   chmod +x fshare
   ```

## Usage

Run the script with the file or directory path as an argument:

```bash
./fshare /path/to/your/file
```

If no path is provided, the script will prompt you to select a file using `fzf`.

### Deleting Files

To delete the uploaded file immediately, use the token provided in the output. You can also check your history in `~/.fshare`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
