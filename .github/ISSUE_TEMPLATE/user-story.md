**As a** online shopper  
**I need** to add items to a shopping cart  
**So that** I can purchase multiple items in a single checkout  

### Details and Assumptions
* Users must be able to add items without being logged in
* Cart should persist for at least 24 hours
* Each item can have a quantity of 1 or more
* Cart should display running total of all items

### Acceptance Criteria
```gherkin
Given I am viewing a product page
When I click the "Add to Cart" button
Then the item is added to my shopping cart
And the cart icon shows the updated item count
And I see a confirmation message
```