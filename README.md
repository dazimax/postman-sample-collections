# postman sample collections
This repository will include postman sample collections to re-use them easily for anyone.

## collection - Magento 2 checkout process with logged-in customer

### local variables

- domain
- adminusername
- adminpassword
- token
- cartId
- sampleSKU
- sampleVariant
- storeCode
- sampleCustomerEmail
- sampleCustomerPassword
- createBraintreeClientToken
- samplePaymentMethod
- createBraintreeClientToken
- braintreeAuth
- braintreeCCToken

![M2 postman variables](/assets/images/m2-postman-variables.png)

### API calls

1. generateCustomerToken
2. createEmptyCart - Registered User
3. Product - Retrieve variant uid values
4. Product - Retrieve variant uid values - Configurable
5. addProductsToCart - Registered User
6. setShippingAddress
7. setBillingAddressOnCart
8. setShippingMethods
9. check Available Payment Methods
10. check Auth TokenizeCreditCard Braintree
11. TokenizeCreditCard Braintree
12. setPaymentMethodOnCart
13. placeOrder

Collection run result:

![M2 checkout process](/assets/images/m2-logged-in-customer-place-order.png)

Cheers! 😉
