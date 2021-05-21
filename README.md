# Compare Electronic Prices - P2_Team_SSJN
This project allows users to find the lowest price for their list of electronic parts. Searching for the right electronic, be it a new phone or computer, can be a daunting task. These are expensive products and the price is an important factor of the purchase. We are saving users time by searching popular electronic websites and stores to find the best price, potentially similar or related products/models, and allow the user to make a decision based on the result of this process.


## Technologies Used
- UiPath Studio
- GitHub

## Installation
To install:
- Git clone this repository 
- Open the project with UiPath studio and run main.

## Usage
Users are required to find their own list of products and for maximum accuracy include the UPC for each product. It should be written in "Sheet2". Users should save their file in data folder in project for easy access though the project can access the file anywhere on the computer. The user simply selects the excel file to analyze and the process will automatically visit BestBuy, MicroCenter, and Newegg and search for the best price. Prices and URLs are recorded in the same excel file in the "results" sheet. The user will then be prompted for their email where the process will send the results to. The sent email will have the product with minimum price with the hyperlink to that product, and the excel sheet containing all of the results 

## Contributors 
Sean Spring, Sean Lee, Jeffery Breiner 

## Licenses
[MIT License](https://github.com/210329-UTA-SH-UiPath/P2_Team_SSJN/blob/main/LICENSE)