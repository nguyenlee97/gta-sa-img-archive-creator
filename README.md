# 🏗️ GTA SA IMG Archive Creator

**Tkinter GUI tool for creating GTA San Andreas IMG v2 archives from source folders.**

## Features

- **Visual queue-based workflow** — add multiple source folders to the conversion queue
- **GTA SA IMG v2 format** — creates archives compatible with GTA San Andreas
- **Save/Load configurations** — INI configuration files for reusable setups
- **Optional source cleanup** — delete source folders after conversion (for release builds)
- **Progress tracking** — real-time progress display with detailed logging

## Screenshot

The tool opens a 900×700 Tkinter window with:
- Folder queue treeview
- Add/Remove folder controls
- Configuration save/load
- Build options (delete source after conversion)
- Progress log

## Requirements

- **Python 3.6+**
- **tkinter** (included with Python on Windows)
- No additional pip dependencies

## Usage

```bash
python img_creation_tool.py
```

## IMG v2 Format

The tool creates standard GTA SA IMG v2 archives:
- Block size: 2048 bytes
- Header with directory entries
- Aligned file data sections

## License

MIT License — see [LICENSE](LICENSE).

## Credits

- Built as part of **Project Eagle** by [@nguyenlee97](https://github.com/nguyenlee97)
