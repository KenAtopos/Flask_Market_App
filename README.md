# Market App
This is a web application built with Flask for buying and selling items in a market place.

# Features

- Home page: welcome and home page
    
    ![home](./market/static/img/register.gif)

- Register: users can register an account
    
    ![register](./market/static/img/check_registration.gif)

- Market: user can see the available items on the market page (unauthenticated users won't be able to access the market page)
    
    ![market](./market/static/img/info_buy_sell.gif)

- Logout: Once user logged out, market page cannot be access
    
    ![logout](./market/static/img/logout.gif)

# Technologies Used
- Python
- Flask
- SQLite (sqlalchemy)
- HTML
- CSS
- Bootstrap

# Getting Started

## Installing
1. Clone the repository:

```
$ git clone https://github.com/KenAtopos/Flask_Market_App.git
$ cd market-app
```
2. Install dependencies:
```
$ pip install -r requirements.txt
```
## Usage
1. Run the app:
```
$ flask run
```
2. Navigate to http://localhost:5000 in your browser.

3. Register an account and start buying and selling items.

