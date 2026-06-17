# Phone Number Information Tracker

A simple Python project that extracts information from a phone number using the `phonenumbers` library. The application provides details such as the country/region, carrier, and associated time zones for a given phone number.

## Features

* Detects the country/region of a phone number
* Identifies the telecom carrier
* Displays the associated time zones
* Supports international phone numbers
* Easy to use command-line interface

## Technologies Used

* Python 3
* phonenumbers library

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/phone-number-tracker.git
```

2. Navigate to the project directory:

```bash
cd phone-number-tracker
```

3. Install the required dependency:

```bash
pip install phonenumbers
```

## Usage

Run the Python script:

```bash
python code.py
```

Enter a phone number in international format:

```text
Enter Your No. with +__: +919876543210
```

### Example Output

```text
Country Code: 91 National Number: 9876543210
('Asia/Calcutta',)
Airtel
India
```

## Project Structure

```text
phone-number-tracker/
│
├── code.py
└── README.md
```

## How It Works

The application uses the `phonenumbers` package to:

1. Parse the phone number.
2. Retrieve associated time zones.
3. Detect the telecom carrier.
4. Identify the country or region.
5. Display the collected information.

## Future Improvements

* Add a graphical user interface (GUI)
* Export results to a file
* Validate user input more effectively
* Support batch phone number analysis

## Author

Rohit Kumar

## License

This project is open source and available under the MIT License.
