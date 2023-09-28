# ecommerceAPI2
This api for ecommerce application and it is very advanced
It has Chat functionality also integrated 
It is developed with nodejs, express and mongodb database
### 1. Clone repo
$ git clone https://github.com/jopaleti/ecommerceAPI2.git

### 2. Setup MongoDB

- Local MongoDB
  - Install it from [here](https://www.mongodb.com/try/download/community)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb://localhost/amazona  
- Atlas Cloud MongoDB
  - Create database at [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - Create .env file in root folder
  - Set MONGODB_URL=mongodb+srv://your-db-connection
 
### 3. Run Backend

```
$ npm install
$ npm start
```
### 4. Seed Users and Products

- Run this on chrome: http://localhost:5000/api/users/seed
- It returns admin email and password
- Run this on chrome: http://localhost:5000/api/products/seed
- It creates 6 sample products
