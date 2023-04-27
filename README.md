# Tool for Encoding and Decoding SAML Requests and Responses

This tool is designed to encode and decode SAML requests and responses. SAML (Security Assertion Markup Language) is an XML-based standard used for exchanging authentication and authorization data between parties, in particular, between an identity provider (IdP) and a service provider (SP).

## Installation

To use this tool, you need to have Node.js and NPM (Node Package Manager) installed on your machine. Once you have them installed, follow these steps:

1. Clone this repository to your local machine.
2. Open your terminal or command prompt and navigate to the root directory of the cloned repository.
3. Run the following command to install the required dependencies:

   ```
   npm install
   ```

4. After the installation is complete, you can start using the tool.

## Usage

To encode or decode a SAML request or response, follow these steps:

1. Open your terminal or command prompt and navigate to the root directory of the cloned repository.
2. Run the following command to start the tool:

   ```
   npm start
   ```

3. Choose the option to encode or decode a SAML request or response.
4. Paste the SAML request or response in the provided input field.
5. Press the `Enter` key to encode or decode the input.
6. The encoded or decoded result will be displayed in the output field.

## License

This tool is licensed under the MIT License. See the `LICENSE` file for more information.

## Credits

This tool was created using the following open-source libraries:

- `samlify`: A JavaScript library for working with SAML requests and responses.
- `inquirer`: A command-line interface for Node.js.
- `clipboardy`: A cross-platform clipboard utility for Node.js.