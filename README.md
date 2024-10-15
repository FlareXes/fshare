# File Share (fshare)

**FShare** is a command-line utility for file sharing. It automatically copies the upload URL to your clipboard for easy sharing. You can also set deletion period of the uploaded file default 24-hours, or delete it immediately.

## Features

- Automatically deletes uploaded files.
- Supports both Wayland and Xorg environments.
- Copies URL to clipboard for effortless sharing.
- Maintain history in `~/.fshare` for easy file management.

## Prerequisites

- **curl**: For HTTP requests.
- **fzf** (optional): For interactive file selection.
- **xclip** (optional): For Xorg clipboard support.
- **wl-clipboard** (optional): For Wayland clipboard support.

## Usage

1. Download the script:

```bash
wget https://raw.githubusercontent.com/flarexes/fshare/main/fshare
```

2. Run the script with the file or directory path as an argument:

```bash
./fshare /path/to/your/file
```

If no path is provided, the script will prompt you to select a file using `fzf`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
