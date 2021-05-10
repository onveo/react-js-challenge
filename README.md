# react-js-challenge
Our ReactJS coding challenge is a simple "Responsive Feed Viewer".

# Main Features of the app

### 1) List of cryptocurrencies
Users should be able to visualize the list of cryptocurrencies they current have on the app

### 2) Current price and percentage change in the last 24h
Users should also be able to visualize: 
* Current price for the cryptocurrencies added
* Change in percentage in USD in the last 24h

### 3) API to get pricing and percentage change
Feel free to use the pricing and percentage change provider of your preference. One of the simplest ones that doesn't require registration is Messari. It provides most of currency short codes such as ETH, BTC. 

You can find a sample bellow:
https://data.messari.io/api/v1/assets/btc/metrics

### 4) Remove a cryptocurrency
From the list, users should be able to remove a cryptocurrency from the "Crypto Tracker".

### 5) Pricing and percentage change update
The Crypto Tracker should update the current price and percentage change in USD to the user. Chose your preferred way to update the data.


Important
---------
All style & cosmetics works should be placed on dynamic style sheet. (SCSS, LESS or any other method)
Minimum required versions:

```
- NodeJs 12+
- ReactJS 16+
- EsLint 7+
```

Readme
------

Regardless of whether it's your own code or our coding challenge, write your README as if it was for a production service. Include the following items:

* Description of the problem and solution.
* Reasoning behind your technical choices, including architectural. 
* Trade-offs you might have made, anything you left out, or what you might do differently if you were to spend additional time on the project.
* Link to other code you're particularly proud of.
* Link to your resume or public profile.
* Link to to the hosted application where applicable.

How we review
-------------

Your application will be reviewed by at least three of our engineers. We do take into consideration your experience level.

**We value quality over feature-completeness**. It is fine to leave things aside provided you call them out in your project's README. The goal of this code sample is to help us identify what you consider production-ready code. You should consider this code ready for final review with your colleague, i.e. this would be the last step before deploying to production.

The aspects of your code we will assess include:

* **Architecture**: how clean is the separation between the front-end and the back-end?
* **Clarity**: does the README clearly and concisely explains the problem and solution? Are technical tradeoffs explained?
* **Correctness**: does the application do what was asked? If there is anything missing, does the README explain why it is missing?
* **Code quality**: is the code simple, easy to understand, and maintainable?  Are there any code smells or other red flags? Does object-oriented code follows principles such as the single responsibility principle? Is the coding style consistent with the language's guidelines? Is it consistent throughout the codebase?
* **Security**: are there any obvious vulnerability?
* **Testing**: how thorough are the automated tests? Will they be difficult to change if the requirements of the application were to change? Are there some unit and some integration tests?
	* We're not looking for full coverage (given time constraint) but just trying to get a feel for your testing skills.
* **UX**: is the web interface understandable and pleasing to use? Is the API intuitive?
* **Technical choices**: do choices of libraries, databases, architecture etc. seem appropriate for the chosen application?

Bonus point (those items are optional):

* **Scalability**: will technical choices scale well? If not, is there a discussion of those choices in the README? 
* **Production-readiness**: does the code include monitoring? logging? proper error handling?

