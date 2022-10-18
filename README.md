# Glance

<p align="center">
  <img src="./img/glance1.png" alt="Logo" height="200">
  <img src = "./img/htn.jpg" alt="Hack the North" height="200">
</p>

## About

Glance is an ingredient scanner that leverages the Cohere NLP word classification API to see if your food has something you don't want in it. Say goodbye to reading labels and have confidence at a glance!

Glance allows users to select an ingredient (like shellfish) or category of food (like dairy) to look for in the picture of the ingredient list they take on our web app. We also provide an option for users to manually enter ingredients they're unsure. The list of ingredients is then checked against the users selected preferences and a table of results ais provided letting the user know at a glance if the food contains any of their flagged ingredients or categories.

This project was developed by Barrett Arbour and Brandon Ye at Hack the North 2022, and was built with React and Node.js. It utilizes Cohere's NLP word classification API on a model trained to classify words into different ingredient catagories.

<p align="center">
  <img src="./img/glance13.jpg">
  <img src="./img/glance14.jpg">
</p>

<details>
  <summary>Screenshots</summary>
  <img src="./img/glance2.png">
  <img src="./img/glance3.png">
  <img src="./img/glance4.png">
</details>

## Usage

To start up the app, clone the repo and run the following commands:

```
node server
```

```
cd client
npm start
```

## Learn More

https://devpost.com/software/glance-vur5we
