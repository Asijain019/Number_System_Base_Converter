# Base Converter GUI

A Python-based graphical user interface application for converting numbers between different numerical bases (binary, decimal, hexadecimal, octal, and any base from 2-16).

## Features

- Convert numbers between any base from 2 to 16
- Support for both integer and decimal number conversion
- User-friendly GUI built with Tkinter
- Error handling for invalid inputs
- Visual logo display
- 
## Requirements

- Python 3.6 or higher
- Tkinter (usually comes pre-installed with Python)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Asijain019/base-converter-gui.git
cd base-converter-gui
```

2. Run the application:
```bash
python nsc2.py
```

## Usage

1. **Enter the number** you want to convert in the "Number" field
2. **Select the source base** (the base of your input number) in the "From Base" field
3. **Select the target base** (the base you want to convert to) in the "To Base" field
4. Click the **"Convert"** button to see the result

### Examples

- Convert decimal 255 to hexadecimal: Input `255`, From Base `10`, To Base `16` → Result: `FF`
- Convert binary 1010 to decimal: Input `1010`, From Base `2`, To Base `10` → Result: `10`
- Convert hexadecimal A to binary: Input `A`, From Base `16`, To Base `2` → Result: `1010`

## Supported Bases

The application supports conversion between bases 2 through 16:
- **Binary (Base 2)**: Uses digits 0, 1
- **Octal (Base 8)**: Uses digits 0-7
- **Decimal (Base 10)**: Uses digits 0-9
- **Hexadecimal (Base 16)**: Uses digits 0-9, A-F
- And any base in between

## File Structure

```
base-converter-gui/
├── nsc2.py              # Main application file
├── README.md            # This file
├── requirements.txt     # Python dependencies
├── .gitignore          # Git ignore rules
├── LICENSE             # MIT License
└── assets/
    └── logo.png        # Application logo
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Known Issues

- The application currently looks for a logo file at a hardcoded path. Make sure to update the path in `nsc2.py` or place your logo in the specified location.

## Future Enhancements

- [ ] Add support for bases higher than 16
- [ ] Implement history of conversions
- [ ] Add keyboard shortcuts
- [ ] Improve UI design and responsiveness
- [ ] Add unit tests

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Created by Asi Jain - feel free to contact me for any questions or suggestions!

## Acknowledgments

- Built with Python's Tkinter library
- Inspired by the need for a simple, reliable base conversion tool
