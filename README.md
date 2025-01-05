# Simple Express Demo

> Express: fast, unopinionated, minimalist web framework for Node.js

This project shows a simple express server serving a single HTML page and using `express.static` to serve static files.

## Endpoints

This project has **7 endpoints**:

1. **Get the hotels sorted by pricing**  
   `GET /hotels/sort/pricing?pricing=low-to-high`

2. **Get the hotels sorted based on their ratings**  
   `GET /hotels/sort/rating?rating=low-to-high`

3. **Get the hotels sorted based on their reviews**  
   `GET /hotels/sort/reviews?reviews=least-to-most`

4. **Filter the hotels based on the hotel amenity**  
   `GET /hotels/filter/amenity?amenity=spa`

5. **Filter the hotels based on the selected country**  
   `GET /hotels/filter/country?country=india`

6. **Filter the hotels based on the selected category**  
   `GET /hotels/filter/category?category=luxury`

7. **Send all hotels**  
   `GET /hotels`

---
## API Hosting

The API has been hosted at:  
[Trip With Us API](https://trip-with-us-api-4ran.vercel.app/)


## Project Demo

The project working can be seen on this site:  
[Hotel Listing Demo](https://bd2-hotel-listing.vercel.app/)
