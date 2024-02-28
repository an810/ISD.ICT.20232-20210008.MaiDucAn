Basic Flow:\
    1. The customer requests to place an order on the view cart screen
    2. The AIMS Software checks the availability of products in the cart
    3. The AIMS Software displays the form of delivery information
    4. The customer enters and submits delivery information
    5. The AIMS Software checks the validity of delivery information
    6. The AIMS Software checks if there is media and the shipping address supported rush order
    7. The AIMS software displays the screen for rush order, allowing the customer to update rush order info if the shipping address and some media support placing rush order.
    8. The AIMS software changes the formula to calculate the shipping fees.
    9. The AIMS software calculates shipping fees. 
    10. The AIMS software displays the invoice. 
    11. The customer confirms to place rush order.
    12. The AIMS software calls UC “Pay rush order.” 
    13. The AIMS software saves order. 
    14. The AIMS software makes the cart empty. 
    15. The AIMS software displays successful order notification.

Alternative Flow:
    1. At Step 5: If the delivery information is not valid -> Notify the customer and ask the customer to input the valid information -> Resume at Step 4
    2. At Step 6: If there is no support either from any media or the shipping address -> Notify the customer and ask to update the delivery information -> Resume at Step 7
    3. At Step 6: If there some media that are not supported (not all) -> Products that do not support rush order will be shipped as normal -> Resume at Step 7
