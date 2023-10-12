# Project - E-commerce Website with instagram-ish reviews (ex.LIPS)

## Description
Makiss is an cosmetics e-commerce Website with instagram-ish reviews (ex. LIPS https://lipscosme.com/).

This online shopping website offers user registration, login, purchasing products, viewing product details, and reading/posting product reviews on each product page. User registration requires an email address, password (8 characters or more), user ID, and a nickname. Users can choose their user ID with their preferred characters, but it needs to be unique. Logging in requires entering the email address and password.

Each user's profile page allows them to register their gender, age group, skin type, hair type, favorite brands, and a self-introduction. Users can change their nickname, user ID, gender, age group, skin type, hair type, favorite brands, and self-introduction upon registration. These details can be updated at any time.

To purchase products, users add items to their cart, proceed to checkout, and provide their name, phone number, email address, and address during the first purchase. This information is stored and doesn't need to be re-entered for future purchases. 

Product details include brand name, product name, a 5-star rating, content volume, and the reference price. Users can post up to ten images or short videos, review comments, color/pattern choices (multiple selections), and a 5-star rating on each product page.

Additionally, from the website's homepage, there's a free-text search feature for reviews, products, and users. The site also includes a ranking function, with rankings categorized by various product categories. Users can view product lists, brand lists, and check new cosmetics in a calendar view. 

Apart from posting product reviews and making purchases, most features on this online shopping site are accessible without user registration or login.

## Entities

- User

- User ID (Unique)
- Email Address
- Password
- Nickname
- Age Group
- Skin Type
- Hair Type
- Favorite Brands
- Self-introduction

- Product

 - Product ID (Unique)
 - Brand Name
 - Product Name
 - Rating (Rated in 5 stars)
 - Content Volume
 - Reference Price

- Cart

 - Cart ID (Unique)
 - User ID (Foreign Key)
 - Product ID (Foreign Key)
 - Quantity

- Order

 - Order ID (Unique)
 - User ID (Foreign Key)
 - Product ID (Foreign Key)
 - Name
 - Phone Number
 - Email Address
 - Address
 - Order Date

- Review

 - Review ID (Unique)
 - User ID (Foreign Key)
 - Product ID (Foreign Key)
 - Images or Short Videos (Up to 10)
 - Review Comment
 - Color/Pattern (Multiple Choices)
 - Rating (Rated in 5 stars)

- Search

 - Search ID (Unique)
 - User ID (Foreign Key)
 - Search Query

- Ranking

 - Ranking ID (Unique)
 - Product ID (Foreign Key)
 - Category
 - Ranking Position
 
