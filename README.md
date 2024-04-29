# NodeJS Test

Create a user table which will have following information
- ID (unique)
- Slug (unique)
- Name
- Password
- Email Address
- Created At
- Updated At

Create a product table which will have following information
- ID (unique)
- Slug (unique)
- Name
- Quantity
- Price
- Owner ID
- Created At
- Updated At

Create a colors table which will have various colors and will have following information
- ID (unique)
- Name

Create a child table called product colors which will have each product’s colors in which product is available with following information
- ID (unique)
- Product ID
- Color ID

Create a REST API for the following
- Signup API to register user into the system
    - User should get an email that you have successfully registered into the system
    - Password should be stored in database using hashed (encrypted)
    - Login API to login user into the system
    - Change Password for logged in user (should be accessible after login)
- List of products with pagination (10 records default)
    - Filters: Available or Not (Based on quantity)
    - Search: Using product name
    - Open API
- Get information about particular product (Using slug)
    - Open API
- Create product information with colors
    - Should be accessible after login
- Update product information (Using slug)
    - Should be accessible after login
    - Only owner of the product can edit his product
- Delete product from database (Using slug)
    - Should be accessible after login
    - Only owner of the product can delete his product


### Notes
- Create a Postman collection and test all API in postman only
- Use MySQL for database
- Use JWT token for authentication
- Handle as much form validations as you can
- Give proper naming convention
- Use SMTP for sending email
