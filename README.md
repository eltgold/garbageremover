# GarbageRemover

**GarbageRemover** is a simple tool designed to help you clean up unnecessary files and "garbage" from your Windows operating system. Whether you're looking to free up disk space or just want to keep your system tidy, GarbageRemover makes the process straightforward and efficient.

## Features

- Removes temporary files and unwanted system clutter
- Lightweight and easy to use
- Safe deletion to prevent removal of important system files
- Customizable: choose which directories or file types to clean
- Fast operation, suitable for regular use

## Installation

Just download the latest release from the [Releases page](https://github.com/eltgold/garbageremover/releases) and run the program. No additional installation is required.

## Usage

> **Note:** The following usage instructions assume the tool is either a script or executable. Adjust as needed based on your implementation.

### Run directly

Double-click the downloaded executable, or run it from the command line:

```sh
garbageremover.exe
```

### Options

- By default, it will clean standard Windows temp directories.
- To specify custom folders or file types, edit the configuration or use command-line arguments (see [Configuration](#configuration) below).

## Configuration

- You can customize the cleaning targets by editing the `config` section in the script or supplying command-line options.
- Example:
  ```sh
  garbageremover.exe --target "C:\CustomFolder" --filetype ".log"
  ```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request. If you find a bug or have a feature request, feel free to open an issue.

## License

[MIT](LICENSE)

## Disclaimer

Use this tool at your own risk. Always make sure you have backups of important data before deleting files from your system.

---

> **Takes off garbage from ur windows ofc lol.**
