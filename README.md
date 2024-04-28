# QR Code Generator

This is a simple QR code generator script written in HTML,CSS,Javascript. It generates QR codes for the given input text or URL and saves them as PNG images.

## Usage

1. Clone this repository or download the `index.html` file.
2. Install the required dependencies by running `pip install qrcode[pil]`.
3. Run the script with the following command:

```
python qr_code_generator.py --text "Your text or URL here"
```

Replace `"Your text or URL here"` with the text or URL you want to encode into a QR code.

4. The generated QR code will be saved as `output.png` in the current directory.

## Options

- `--text`: Specify the text or URL to encode into the QR code (required).
- `--output`: Specify the output file name (default is `output.png`).
- `--size`: Specify the size of the QR code image (default is 200x200 pixels).

## Example

Generate a QR code for the URL "https://example.com" with a custom output filename:

```
python qr_code_generator.py --text "https://example.com" --output "example_qr_code.png"
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
