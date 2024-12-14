# Payment System Design
This project will replicate a payment processor's system(like Paypal, Stripe, etc.), providing services written in REST API.

The payment processor in real life is more complicate since it will interact with issuer, requring banks, here I will only trying to build a micro-service that does the following:
1. User purchase something from a merchant's website
2. User's balance get deducted 
3. Merchant's balance increases

The technologies involved to support the requirement:
1. Client: Use Javascript to take and make requests to the server
2. Server:
    1. Use OOP to design user and merchant object
    2. Use REST API to design the API to support main functions
    3. Use NoSQL to store the transactions

## Design Practice:
### Secruity
1. [Nice-to-have] Use encryption for user's data

### Scalability
1. Use asynchronous programming on both client and server side's code

