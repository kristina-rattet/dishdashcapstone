# DishDashDelivery


## Description

DishDashDelivery serves as my submission for MIT xPro Women's Cohort Professional Certificate in Coding Program's final capstone project. This fictional restaurant delivery app demonstrates my comprehension and execution of full-stack web development using MERN.

Users have the ability to create an account and subsequently login as either a restaurant or a customer. Restaurants have the ability to create and edit restaurant details, logos, images, and menu items, including dish name, descriptions, images, pricing. Customers have the ability to add or remove dishes to/from their cart, modify quantity, and complete their checkout using Stripe as their secure payment method.


## Functionalities

- Filter restaurants by cuisine types
- Add various restaurant dishes to the cart ("doggy bag")
- Modify quantity or delete dishes through the cart
- Real-time updates of cart subtotal
- Navigate through images and descriptions of available dishes
- Revolving carousel of restaurat images on home page
- 

Create an account as either a customer or restaurant
- Log-in and log-out
- Search for restaurants by name
- Search for specific dishes within a restaurant
- Add dishes to your cart and adjust quantity
- Modify quantity of dishes on cart
- Real-time updates of payment subtotals
- Secure checkout with Stripe
- Register as a restaurant account
- Upload or edit restaurant picture, logo, name, and description
- Create, modify, and delete dishes, including item name, image, description, and price.

## Future Adds

- Ability to search for restaurants by name
- Ability to sign up for VIP discount and apply coupon code

## How to Run

Fork this repository or download the zip file and open within your preferred code editor (I used VS Code)


cd DishDash
npm install
```



Once you have set up the environment variables, you can safely run the application in your computer by running `npm run dev`. Then open [localhost:3000](http//localhost:3000) in your browser.

## Tech Specifications

- Framework: [NextJS](https://nextjs.org/)
- Hosting Service: [Vercel](https://vercel.com/)
- API Approach: [REST](https://aws.amazon.com/what-is/restful-api/)
- API Documentation: Swagger.
- Database: [MongoDB](https://www.mongodb.com/)
- Secondary Storage: [AWS S3](https://aws.amazon.com/s3/)
- Payment Getaway: [Stripe](https://stripe.com/)
- Authorization and Authentication: [JSON Web Tokens](https://jwt.io/)
- Important libraries: [@aws-sdk/client-s3](https://docs.aws.amazon.com/AWSJavaScriptSDK/v3/latest/clients/client-s3/index.html), [stripe](https://stripe.com/docs/api), [mongoose](https://mongoosejs.com/), [cookies-next](https://www.npmjs.com/package/cookies-next), [next-swagger-doc](https://www.npmjs.com/package/next-swagger-doc), [general-formatter](https://www.npmjs.com/package/general-formatter)

## Images

### Home and Restaurant List

![Home](./public/Home.png)

![RestaurantList](./public/Home-restaurants.png)

### Restaurant Dishes

![RestaurantDishes](./public/Restaurant-dishes.png)

### Cart and Checkout

![Cart](./public/Cart.png)

![checkout](./public/Checkout.png)

### User Orders

![UserOrders](./public/MyOrders.png)

### Restaurant Admin

![RestaurantAdmin](./public/restaurant-admin.png)

## Created by

[Kristina Rattet](https://www.linkedin.com/in/kristina-rattet/)

## License

MIT License

## Images Sourced From

[unsplash.com](https://unsplash.com/)
