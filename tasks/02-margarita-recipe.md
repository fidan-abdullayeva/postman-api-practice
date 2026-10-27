Task 2: Margarita Recipe
Objective
To retrieve Margarita recipe information using an existing recipe API.

API Request
- HTTP Method: GET
- Endpoint: "https://api.api-ninjas.com/v3/recipe"
- Query Parameter: "title=margarita"
- Header: "X-Api-Key"

cURL Request
curl --location 'https://api.api-ninjas.com/v3/recipe?title=margarita' \
--header 'X-Api-Key: YOUR_API_KEY'

Response
The API returns recipe information matching the Margarita title query.
- Status Code: 200 OK

Tools Used
- Postman
- API Ninjas Recipe API

## Screenshot
![Margarita Recipe] (../margarita-recipe.png)
