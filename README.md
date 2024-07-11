
# Prebuilt Checkout Page with Subscriptions

Welcome to our fully functional integration with Stripe Checkout and the Customer Portal. This sample provides both client- and server-side code to demonstrate how to redirect users to a prebuilt payment page hosted by Stripe. We’ve also included some basic build and run scripts to help you get started quickly.

## Getting Started

Follow these steps to build and run the application:

1. **Install Dependencies**

   Run the following command to install the necessary dependencies:

   bash
   npm install
   

2. **Start the Application**

   Once the dependencies are installed, start the application with:

   bash
   npm start
   

3. **Access the Checkout Page**

   Open your browser and go to [http://localhost:3000/checkout](http://localhost:3000/checkout) to see the prebuilt checkout page in action.

## Payment Mode Configuration

Our application provides flexibility in handling different payment scenarios using Stripe's mode parameter. Here are the available modes and their uses:

### Subscription Mode

Use subscription mode to store the payment details of the customer. This mode is ideal for subscription-based services, allowing you to charge customers on a recurring basis.

javascript
mode: 'subscription'


### Setup Mode

Use setup mode to store the payment details of the customer in advance, without immediately charging them. This allows you to charge the customer at a later time when needed.

javascript
mode: 'setup'


### Payment Mode

Use payment mode to accept one-time payments. This mode supports various payment methods, including cards and iDEAL, making it suitable for single, immediate transactions for goods or services.

javascript
mode: 'payment'


## Need Help?

For more information and consultation, please visit our website at [https://crabroom.com](https://crabroom.com) or book a meeting at [https://crabroom.com/contact](https://crabroom.com/contact).

Thank you for using our sample! We hope it helps you integrate Stripe Checkout seamlessly.
