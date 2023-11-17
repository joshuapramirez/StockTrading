# Stock Trading Application

## Overview
The Stock Trading Application is a simulation platform inspired by services like TDAmeritrade. Users can look up stock prices, simulate buying and selling of stocks, and track their virtual portfolio. The application is built on Flask and utilizes the IEX Cloud API for real-time stock data. Users need to sign up for a free trial at [https://iexcloud.io/](https://iexcloud.io/) to obtain an API key for accessing stock data.

# Installation

To run the Stock Trading Application locally, follow these steps:

1. Clone the repository: `git clone https://github.com/joshuapramirez/stock-trading.git`
2. Navigate to the project directory: `cd stock-trading`
3. Install dependencies: `pip install -r requirements.txt`

### Set up IEX Cloud API Key

- Obtain an API key by signing up at [https://iexcloud.io/](https://iexcloud.io/).

Option1:
- Set the API key as an environment variable in your terminal session:

  ```bash
  export IEX_API_KEY=your-api-key

  Replace your-api-key with the API key you obtained from IEX Cloud.

Option2:
- Configure Environment Variables
  - Create a '.env' file in the project root.
  - Add the following line to the .env file:
      IEX_API_KEY=your-api-key

      Replace your-api-key with the API key you obtained from IEX Cloud.

## Usage
1. Start the Flask application: `python app.py`
2. Open your browser and go to [http://localhost:5000](http://localhost:5000)
3. Explore stock prices, buy/sell stocks, and track your virtual portfolio.


## License
This project is licensed under the [MIT License](LICENSE).
