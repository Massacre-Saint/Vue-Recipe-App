# Recipe App

This recipe app lets users search for recipes by ingredients and save their favorites.

## Lessons Learned

My learning object for this app was to implement a store to eliminate prop drilling.

- Focus on state management.

## Installation

Run recipes with npm

```bash
  cd recipes
  npm run dev
```

## Tech Stack

**Client:** Vue, JS, PrimeFlex, PrimeIcons, Vite

## API Reference

### Spoonacular API

Use the Spoonacular Web API to search for recipes by ingredients. The API is free but you will need to [sign up here](https://spoonacular.com/food-api/console#Dashboard) for a key before you can use it.

```http
https://api.spoonacular.com/recipes/random?tags=apples,sugar&number=8&apiKey=YOUR_API_KEY
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `tags`    | `string` | **Required**. Id of item to fetch |
