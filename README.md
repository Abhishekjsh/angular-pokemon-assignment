# angular-pokemon-assignment

Pokemon details and Listing Application is used to show pokemon list, pokemon details, create product and product list please find the below features of this application.

- Show all Pokemons in Home tab.
- Able to select a pokemon from list and show its detail imformation in detail section.
- Show all Pokemons Details in Details tab.
- Able to add new product, add maximum 5 product at a time.
- Show all new products in product list tab.
- Able to search.
- At Home tab next and previous button used to show next and previous pokemons.
- Tabs rendering depends on isAdmin flag which is present in user.service.ts.
- If isAdmin = true, render all four tabs and if it is false only home and detail tab render.
- All the information save from create product is store in localstorage.
- If there are not any product present in localstore product list tab is not active using canActivateGuard.
- During searching if no record found it should not redirect to detail tab using guards and show error message.
- we show loader during Api calls.
- All page and design are responsive for all mobile screens.
- validation error messages displays if we enter min length in search box.
- No Any console Error warnings.
- Implement forkJoin operator for parallel API calls.
- Use ES6 Feactures.
- Provide proper code documentation.
- Define proper function param and return type.
- Define Models for data.
- Use Prettier for formatting.
- We should not use Public keyword, by default all props and methods public.
- Use private keyword at relevant places.
- We handle wild card routing.
- No Any inline css used in project
- All the error messages, urls and min/max length comes from system.constants.ts file.

> The goal of this project to show pokemon list and render pokemons detail and create products and render them in product list.

#### Create product has following things:

- Field type
- Validations(required, min, max, regx(for url, number and decimal))
- Save button
- Reset Button
- Add New Product Button
- All Error messages, regex and min/max length comes from system constants.

### Tech

- [Angular 9] - HTML enhanced for web apps!
- [BootStrap 4] - UI components

### Installation

Take clone from

```
$ git clone https://github.com/Abhishekjsh/angular-pokemon-assignment
```

Install the dependencies.

```
$ cd angular-pokemon-assignment
$ npm install
$ ng serve
Open http://localhost:4200 in browser
```
