Test Cases & Execution — E-commerce Website (MAKEUP)
TC_01 — Verify homepage loading

Preconditions: Website URL is доступний.
Steps: Open homepage.
Expected Result: Homepage loads successfully without errors.

Priority: High
Status: ✅ Pass

TC_02 — Verify search with valid input

Preconditions: User is on homepage.
Steps:

Enter valid product name.

Click Search.

Expected Result: Relevant products are displayed.

Priority: High
Status: ✅ Pass

TC_03 — Verify product details page

Preconditions: Search results are displayed.
Steps: Click on any product.

Expected Result: Product page opens with description, price, and images.

Priority: High
Status: ✅ Pass

TC_04 — Verify adding product to cart

Preconditions: Product is in stock.
Steps: Click "Add to Cart".

Expected Result: Product is added to cart successfully.

Priority: High
Status: ✅ Pass

TC_05 — Verify removing product from cart

Preconditions: Product is in cart.
Steps: Click Remove button.

Expected Result: Product is removed from cart.

Priority: Medium
Status: ✅ Pass

TC_06 — Verify checkout page opening

Preconditions: Product is in cart.
Steps: Click Checkout.

Expected Result: Checkout page opens successfully.

Priority: High
Status: ✅ Pass

TC_07 — Verify search with invalid characters

Preconditions: User is on homepage.
Steps:

Enter "@@@###" in search field.

Click Search.

Expected Result: System displays "No results found".

Actual Result: System displays 112 products.

Priority: Medium
Status: ❌ Fail

👉 Bug Report created.

TC_08 — Verify adding out-of-stock product

Preconditions: Product marked as "Out of stock".
Steps: Click "Add to Cart".

Expected Result: System prevents adding product and shows message.

Priority: High
Status: ✅ Pass

TC_09 — Verify browser console errors

Preconditions: Website is open.
Steps:

Open Chrome DevTools.

Navigate through main pages.

Expected Result: No critical errors in console.

Priority: Medium
Status: ✅ Pass


Хочеш одразу оформимо його у форматі для GitHub?
