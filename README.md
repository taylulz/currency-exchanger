
# Currency Exchanger

#### Exchange rates for global currencies using Fetch API calls. 11.20.2020

#### By _**Taylor Delph**_

## 🚩 Description

An independent Friday project for Epicodus utilizing a Fetch API call, asynchronous code, and a working development environment. This application will convert a selected currency amount into various different currencies.

## Stretch Goals
- Build out a user interface that looks very finance-y

## 🔧 Setup/Installation Requirements

### Software Requirements

- To run this project locally you will need to have node. You can check if you have node by running `node -v` in the command line. If you do not have node please find more information and download [here](https://nodejs.org/en/download/)

- You will also need to have an ExchangeRate-API key. To get this you will need to request a Key [here](https://www.exchangerate-api.com/).

### Open Locally

#### Opening using GitHub Desktop:
Go to my GitHub repository here [](), and click on the green 'Code' button to clone the repository, Open with GitHub Desktop OR Download the ZIP file

#### To clone using the Command Line:
1. Push the green 'Clone' button and copy the URL.
2. Open Terminal or GitBash and input the command: `git clone {LINK}`
3. To view the code, open the copied directory with Visual Studio Code or your preferred text editor by inputing the command `code .` in your terminal.
4. To view the website, open index.html in Chrome or your preferred browser.

### Run environment:

1. Run `npm install` in terminal.
2. Create a `.env` file in the root directory.
3. Save your API key in the `.env` by inputting `API_KEY={Your_API_Key}`. There should be no spaces in here.
4. Input `npm run start` to view the live server for the application.

## 🐛 Known Bugs

_No known bugs at this time_

## 📫 Support and contact details

Please contact me via email:
- [Taylor's email](mailto:taylulzcode@gmail.com)

## 🛠️ Technologies Used

This project uses the following technologies:

- JavaScript
- JQuery
- HTML
- CSS
- Bootstrap
- GitHub
- VS Code
- webpack
- npm 

## 📘 License

MIT License

Copyright (c) 2020 Taylor Delph

## Specifications
| Test | Input | Output |
|--------|:------:|:-----:|
| **Describe ExchangeService:** |||
| Should correctly return json object if call is successful | standard endpoint | world currency exchange rates |
| Should correctly return error if call is unsuccessful | standard endpoint | error |
| Should correctly use user selected base currency for api call | USD | http://enpoint_USD |
| Should correctly display user selected base currency & amount | 100 USD | 100 USD |
| Should correctly divide user selected base currency and amount by Destination Currency exchange rate | 100 USD | 109.67 CHF |
