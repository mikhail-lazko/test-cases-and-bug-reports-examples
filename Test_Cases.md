### [TC-1] Item purchase
| # | Steps                             | Expected Results                               |
| :-| :-------------------------------- | :--------------------------------------------- |
| 1 | Log in as standard_user           | Inventory page is displayed                    |
| 2 | Add any item to the shopping cart |                                                |
| 3 | Open the shopping cart            |                                                |
| 4 | Click 'Checkout' button           | 'Checkout: Your Information' page is displayed |
| 6 | Fill in 'First Name', 'Last Name', </br> 'Zip/Postal Code' fields with valid data ||
| 7 | Click 'Continue' button           | 'Checkout: Overview' page is displayed         |
| 8 | Click 'Finish' button | 'Checkout: Complete!' page is displayed with Success Message:</br>'<strong>Thank you for your order!</strong></br>Your order has been dispatched, and will arrive just as fast as the</br>pony can get there!'                 |

##

### [TC-2] Log in with not existing credentials
| # | Steps                                                             | Expected Results  |
| :-| :---------------------------------------------------------------- | :---------------- |
| 0 | Repeat step #1, #2 for the next set of credentials:</br>1. Not existing username + Not existing password</br>2. Existing username + Not existing password</br>3. Not existing username + Existing password                               |                   |
| 1 | On the login page, enter the specified combination of credentials |                   |
| 2 | Click 'Login' button                                              | 1. Login page is displayed</br>2. Error message is displayed:</br>'Epic sadface: Username and password do not match</br>any user in this service '                                        |

##

### [TC-3] Inventory Item page UI elements
| # | Steps                                                      | Expected Results                                                                                  |
| :-| :--------------------------------------------------------- | :------------------------------------------------------------------------------------------------ |
| 1 | Log in as standard_user                                    | Inventory page is displayed                                                                       |
| 2 | Memorize any item title, image, price, and click the title | Inventory Item page for the item is displayed                                                     |
| 3 | Verify UI elements on the Inventory Item page              | 1. Header with menu button, 'Swag Labs' logo, cart icon</br>2. Secondary header with 'Back to products' button </br>on the left under the generic header</br>3. Inventory Item container with:</br>- Image from the step 2 on the left</br>- Title from the step 2</br>- Item description</br>- Price from the step 2</br>4. 'Add to cart' button</br>5. Footer with social media icons (Twitter, Facebook, LinkedIn),</br>Copyright text|