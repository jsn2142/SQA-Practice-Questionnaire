# QA Engineer Assessment
<a name="readme-top"></a>
Please read all the instructions below to prepare for the assessment.
## UI Automation
* Prerequisite: Register as a user on the [website](https://juice-shop.herokuapp.com/#/).

### Test scenario 01:
1. Login with the user that you just registered. Assert the user is registered with the same email address.
2. Using search, add 2 different items to the basket, one item with one unit, another one with 2 units.  
3. Assert the items available in the basket with the units and prices.
4. Click on checkout. Add a new address and select the added address to continue.
5. For Delivery, select “Standard Delivery” and assert that the next page is shown afterwards.
6. In the Payment Options, add a new card and after adding it, select the card and proceed to the next page.
7. For the Order Summary page, assert with the total price of the selected items and their price.
8. After placing the order, confirm the delivery address for assertion.

### Test scenario 02:
1. Login as the user, search for the items that you order earlier. Verify that the items are shown properly after search.
2. Click on the products and give that product a review. For assertion, verify that the review is showing properly with the registered email address.
n.b. Do this for both products one after another.

## API Automation
### Test scenario 01:
1. Login with the user. 
2. Add 2 items to the basket, with one having 2 units and another having 3 units.
3. Verify the items with the unit quantity in the basket.

### Test scenario 02: 
1. Register a new user.
2. Login with this new user.
3. Check the basket, verify it has zero items in it.
4. Add 3 items in it, each having different units. 
5. Delete the last item from the basket. Verify the remaining two items in the basket with the correct quantity.

## Notes:
* You are free to use any automation tool/framework for the UI and API automation(i.e. Cypress, Selenium, WebdriverIO, Postman, etc)
* Be creative with the assertions, as long as it makes sense.
* Make sure to generate a report in your automation script.
* Use reuseable functions for the scripts.
* Upon completion, upload the code in your Github repository, submit the link in the reply. Keep the repo public.
* Add screen recordings of all the automation tests along with the Github Repository link.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
