# woocommerce-check-card-expiry

It is woocoomerce customization which includes :

1. Adding acitvation and deactivation details to order meta.
2. Adding custom field to woocommerce orders for inserting card number in wordpress admin => woocommerce => Orders => edit any order.
3. Create shortcode for a search form to check card numbers.
4. Verification of card number with expiry date for a particular order.

Usage Instructions: 

1. Add a product with title "event ticket" (this code will work for the product with "event ticket" title only, we just need to remove few lines of code to make it working for all products).
2. Copy code after line number: 588 from this functions.php file to your functions.php file to make it working for you.
3. Order your product with name "event ticket" and then go to wordpress admin => woocommerce => Orders
4. Edit your order, put card number and update.
5. Now use this shortcode [card_search] to show search form.
6. Check expiry time remaining for that card number.

We can customize it in many ways as per our requirement.
