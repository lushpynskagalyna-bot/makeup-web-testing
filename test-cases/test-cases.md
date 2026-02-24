Test Cases — E-commerce Website (MAKEUP)

TC_01 — Verify search functionality with valid keyword

Preconditions:
User is on the homepage.

Steps:

Enter a valid product name.

Click Search.

Expected Result:
Relevant products are displayed.

Priority: High
Type: Functional

TC_02 — Verify search with invalid input

Preconditions:
User is on the homepage.

Steps:

Enter invalid characters (e.g., "@@@###").

Click Search.

Expected Result:
System displays "No results found" message.

Priority: Medium
Type: Negative

TC_03 — Verify adding product to cart

Preconditions:
Product is in stock.

Steps:

Click "Add to Cart".

Expected Result:
Product is added to cart successfully.

Priority: High
Type: Functional

TC_04 — Verify adding out-of-stock product

Preconditions:
Product is marked as "Out of stock".

Steps:

Click "Add to Cart".

Expected Result:
System prevents adding product and displays message.

Priority: High
Type: Negative

TC_05 — Verify removing product from cart

Preconditions:
Product is in cart.

Steps:

Click Remove button.

Expected Result:
Product is removed from cart.

Priority: Medium
Type: Functional

TC_06 — Verify no critical errors in browser console

Preconditions:
Website is open.

Steps:

Open DevTools console.

Navigate through main pages.

Expected Result:
No critical errors appear in console.

Priority: Medium
Type: Technical
