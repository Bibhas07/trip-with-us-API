# Simple express demo

> Express: fast, unopinionated, minimalist web framework for Node.js

This project shows a simple express server serving a single HTML page and using `express.static` to serve static files.

This Project has 7 endpoints:
Endpoint 1: Get the hotels sorted by pricing(hotels/sort/pricing?pricing=low-to-high)
Endpoint 2: Get the hotels sorted based on their Ratings(hotels/sort/rating?rating=low-to-high)
Endpoint 3: Get the Hotels sorted based on their Reviews(hotels/sort/reviews?reviews=least-to-most)
Endpoint 4: Filter the hotels based on the Hotel Amenity(hotels/filter/amenity?amenity=spa)
Endpoint 5: Filter the hotels based on the selected Country(hotels/filter/country?country=india)
Endpoint 6: Filter the hotels based on the selected Category(hotels/filter/category?category=luxury)
Endpoint 7: Send all hotels(/hotels)

The Project working can be seen in this site(https://bd2-hotel-listing.vercel.app/)
