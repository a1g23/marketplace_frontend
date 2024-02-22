# Barter Circus Frontend

- **Alex Greenberg**
- **Rohan Sinha**
- **Nicholas Murray**
- **Daniel Ji**

**The Barter Circus App will help vendors display items for sale. Think online yard sale!**

**netlify website**

## List of Dependencies

- React
- React Router
- Sass


## Frontend Route Map

| Route Name | Path | Element | Action | Description |
|------------|----------|--------|----------|-------------|
| Item Index | ""  | ShowAll  |  N/a  |  Renders all of the Item on a page |
| Create Item | "create" |  N/a  | createAction | Creates the new Item from the form |
| Update Item | ":id" |   N/a  | updateAction | Updates the existing Item from the form  |
| Remove Item | "delete/:id" | N/a | deleteAction | Deletes the Item selected |
| Show Item | ":id" | ShowOne | N/a | Renders a detailed page of the Item |


## React Architecture
![React Architecture](./frontendERD.png)

## Web and Mobile Mockups
![Desktop Mockup](https://i.imgur.com/HjFupZe.png)
![Mobile Mockup](https://i.imgur.com/OCQoMgc.png)