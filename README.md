# Option_Price_Calculator
This is a Django-based website that allows users to calculate option prices using the binomial n-step model and the Black-Scholes model.

## Features

- Calculation of option prices using the binomial n-step model
- Calculation of option prices using the Black-Scholes model
- User-friendly interface for inputting option parameters
- Clear and concise display of calculated option prices

## Setup

Follow these steps to set up Option Price calculator locally:

### Prerequisites

- Python 3.x
- Django
- `scipy`, `numpy`, and `math` libraries

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/SriChaitu/Option_price.git
   ```

2. Change to the project directory:

   ```bash
   cd Option_price
   ```

3. Create a virtual environment:

   ```bash
   python3 -m venv venv
   ```

4. Activate the virtual environment:

   - For Windows:

     ```bash
     venv\Scripts\activate
     ```

   - For macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

5. Run the application:

   ```bash
   python manage.py runserver
   ```

6. Access the application:

   Open a web browser and go to `http://localhost:8000` to access the Option price calculator locally.

## Usage

- On the home page, you will see options to calculate prices using the binomial n-step model and the Black-Scholes model.
- Select the desired model.
- Enter the required option parameters, such as the stock price, strike price, time to expiration, risk-free rate, volatility, etc.
- Click on the "Calculate" button to obtain the option price.
- The calculated option price will be displayed on the page.
- You can perform multiple calculations by entering different parameters and clicking the "Calculate" button again.


## Screenshots
![Screenshot (292)](https://github.com/SriChaitu/Option_price/assets/95231920/8926cac9-464b-4562-9b41-da3737edd463)
![Screenshot (293)](https://github.com/SriChaitu/Option_price/assets/95231920/cda55cd6-2267-4ff2-bdf4-8ac8fc273ea3)
![Screenshot (294)](https://github.com/SriChaitu/Option_price/assets/95231920/60605975-418e-4f18-a521-9309fa344d27)
![Screenshot (295)](https://github.com/SriChaitu/Option_price/assets/95231920/2c16f3a7-6279-4466-a2d8-937d225ce1d0)
![Screenshot (296)](https://github.com/SriChaitu/Option_price/assets/95231920/cd612703-975a-4e08-8473-18b4663cec37)
![Screenshot (297)](https://github.com/SriChaitu/Option_price/assets/95231920/ad1f3cd1-a5bd-425f-a815-624de7caae60)
![Screenshot (298)](https://github.com/SriChaitu/Option_price/assets/95231920/b1245079-92c5-41c1-8a4e-a248afffb4d3)


## License

Option price calculator is released under the [MIT License](LICENSE).
