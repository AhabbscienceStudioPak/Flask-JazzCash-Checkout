# Flask JazzCash Checkout
Setting up JazzCash Checkout with Flask.
This repository contains a Flask application that demonstrates the integration of the JazzCash payment gateway.

## Prerequisites

Before running the application, make sure you have the following:

- Python installed
- Flask framework installed
- JazzCash merchant credentials (Merchant ID, Password, Integrity salt)

## Configuration
Open the main.py file and update the following configuration variables:

```python
JAZZCASH_MERCHANT_ID = "<JAZZCASH_MERCHANT_ID>"
JAZZCASH_PASSWORD = "<JAZZCASH_PASSWORD>"
JAZZCASH_RETURN_URL = "<JAZZCASH_RETURN_URL>"
JAZZCASH_INTEGRITY_SALT = "<JAZZCASH_INTEGRITY_SALT>"
```
Replace <JAZZCASH_MERCHANT_ID>, <JAZZCASH_PASSWORD>, <JAZZCASH_RETURN_URL>, and <JAZZCASH_INTEGRITY_SALT> with your actual JazzCash merchant credentials and desired return URL.

## Usage
Run the Flask application:
```shell
python main.py
```
Access the application in your web browser at http://localhost:5000.

Click on the "Checkout with JazzCash" button to initiate the payment process.
