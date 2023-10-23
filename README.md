# ourlaces.sports
Introducing Our Laces, an online store developed with Material-UI (MUI) for the user interface and the MERN (MongoDB, Express, React, Node.js) stack. 
This project offers a wide range of tools to improve the shopping experience, in both admin and regular user modes.
# Tech Stack
MongoDB      
Express      
React      
Node.js       
Material-UI     
Stripe      
Mongoose      
Redux       
Redux-thunk 
CSS3

# Project Configuration Guide
## Cloudinary Configuration
Cloudinary is used for image management and hosting.
Follow these steps to configure Cloudinary for your project.
Create a Cloudinary account here.
Create a new Cloudinary project.
Go to the dashboard and copy the cloud name, API key, and API secret.
## Stripe Configuration
Stripe is used for payment processing.
Follow these steps to configure Stripe for your project.
Create a Stripe account here.
Go to the dashboard and copy the publishable key and secret key.
## Nodemailer Configuration
Nodemailer is used for sending emails. 
Follow these steps to configure Nodemailer for your project.
Create a Gmail account here.
Go to the account settings and enable the Less Secure App Access.
Go to the dashboard and copy the email and password.
Go to .env file and save SMTP_MAIL and SMTP_PASS.
If you are using Gmail, you can directly copy the email and password. If you are using any other email service, you need to copy the SMTP host, port, and service.
Repl
## MongoDB Configuration
MongoDB is used for storing data. Follow these steps to configure MongoDB for your project.
Create a MongoDB account here.
Create a new project and cluster.
Go to the dashboard and copy the connection string.
Go to .env file and save DB_LINK.

# Installation
1. Clone the repository:

git clone https://github.com/MehraDevesh2022/CricketWeapon-Store.git
cd CricketWeapon-Store

2. Install dependencies:

npm install
cd frorntend
npm install
cd ..

3. Create a config folder inside the backend directory of the project and then create a .env file inside the config folder and add the following:

PORT = 5000
DB_LINK ="mongodb+srv://<username>:<password>@<cluster-url>/<database-name>?retryWrites=true&w=majority"
NODE_ENV = production
JWT_SECRET = <jwt-secret-key>
JWT_EXPIRE = 5d
COOKIE_EXPIRE = 5
SMTP_HOST=smtp.gmail.com
SMTP_PORT=465
SMTP_SERVICE = gmail
SMTP_MAIL = <smtp-email>
SMTP_PASSWORD = <smtp-password>
SMTP_PASS = <smtp-password>
CLOUDINARY_NAME = <cloudinary-name>
API_KEY = <api-key>
API_SECRET = <api-secret>
CLOUDINARY_URL=cloudinary://<api-key>:<api-secret>@<cloudinary-name>
FRONTEND_URL = http://localhost:3000
STRIPE_API_KEY = <stripe-api-key>
STRIPE_SECRET_KEY = <stripe-secret-key>

4. Run the app:

cd backend &&
npm start
# Feature	Description
Sales Analytics	Gain insights into sales trends and popular products
Dynamic Coupons	Create and manage targeted coupons
User Analytics	Track user engagement and activity
Bulk Product Upload	Upload and update multiple products using CSV
Automated Emails	Send automated emails for order confirmation and updates
Notification Center	Receive alerts for new orders, low stock, and more
Data Export	Export data sets (e.g., orders, products) to CSV or Excel
Product Bundles	Create and manage product bundles
