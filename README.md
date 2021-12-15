# RestockingCart Project

# Description

Shopping RestockingCart App is part of assignments for the Week 19 in the [Professional Certificate in Coding: Full Stack Development with MERN](https://xpro.mit.edu/programs/program-v1:xPRO+PCCx+R1/). In this App, I use javascript and React.js, along with Strapi to store products data and a call an database API for restocking.

### License: [MIT License](https://opensource.org/licenses/MIT)
## How to Run

You can download the source code cloning this repository using Git:

1. Open your favorite Terminal app (Unix, Linux or Macos), such as Terminal, Command, Console, iTerm2, so on.

2. Clone the repository
```
git clone https://github.com/dicotips/RestockingCart.git
```

3. Be sure that you have Strapi 3.6.8

```
npx create-strapi-app@3.6.8 cartDB --quickstart
```

3.1. Add in the table "products" the followign content, and publish it and add public permissions

```
{ name: "Apples_", country: "Italy", cost: 3, instock: 10 },
{ name: "Oranges", country: "Spain", cost: 4, instock: 3 },
{ name: "Beans__", country: "USA", cost: 2, instock: 5 },
{ name: "Cabbage", country: "USA", cost: 1, instock: 8 },
```

Test Strapi API calling:  ```http://127.0.0.1:1337/products```
