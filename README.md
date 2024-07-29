# vin-lookup
VIN Decoder and Reporting Service

This project is a simple web service that decodes a Vehicle Identification Number (VIN) to provide the make, model year, and manufacturing plant of a vehicle, as well as accident and theft reporting.

## Features
- Decodes the first 3 characters of the VIN to determine the make and manufacturing plant.
- Extracts the 10th character of the VIN to determine the model year.
- Basic error handling for invalid VIN input.

## Usage
1. Enter a 17-character VIN number in the input box.
2. Click the "Decode" button.
3. View the make, model year, and manufacturing plant information.

## Installation
1. Clone the repository: `git clone https://github.com/chrlzs/vin-lookup.git`
2. Navigate to the project directory: `cd vin-lookup`
3. Install dependencies: `npm install`
4. Start the server: `node server.js`
5. Open `index.html` in your web browser to use the VIN lookup.

## License
This project is licensed under the MIT License.

## Contributions
Contributions are welcome! Feel free to fork this repository and submit pull requests.

## Contact
For questions or suggestions, please open an issue or contact me directly.
