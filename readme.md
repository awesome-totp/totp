# TOTP Generator

The TOTP Generator is a web-based application designed to generate secure time-based one-time passwords (TOTP) for two-factor authentication (2FA). This tool enhances user security by providing a unique TOTP every time it is required, using standardized algorithms compliant with the specifications in RFC 6238.

## Features

- **Secure Token Generation**: Generates TOTP based on a secret key that conforms to the Base-32 format, ensuring strong security.
- **Dynamic Key Generation**: Users can generate a new secret key at any time with the click of a button, ensuring that keys can be rotated easily and securely.
- **User-Friendly Interface**: The application features a clean, intuitive interface that is easy for users to navigate and use.
- **Customizable Token Configuration**: Users can customize the number of digits in the token and the token period (e.g., 30 seconds or 60 seconds), allowing for flexibility in how tokens are generated according to specific security needs.
- **Clipboard Support**: Users can easily copy the generated token to the clipboard with a single click, enhancing usability.
- **Responsive Design**: Designed to work on both desktop and mobile devices, ensuring access across all platforms.
- **Vue.js Frontend**: Leveraging the capabilities of Vue.js for a reactive and component-driven architecture.

## Usage

1. **Access the Application**: Open the web application in your browser.
2. **Generate or Enter a Secret Key**: Use the provided button to generate a new secret key or enter an existing one if you have it.
3. **Configure Token Settings**: Set the desired number of digits and the token period based on your preference or system requirements.
4. **Generate TOTP**: The TOTP is automatically updated at every interval set by the token period. Use the copy button to copy the token to your clipboard.

## Credits

This tool uses [Crypto Exchange Software](https://codono.com) for its backend operations, ensuring reliable and secure management of cryptographic operations.

## Contributing

Contributions to the TOTP Generator are welcome. Please ensure that your pull requests provide a clear description of what you are changing and why.

## License

This project is licensed under the MIT License 

