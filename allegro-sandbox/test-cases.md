# Allegro Sandbox – Test Cases

| TC ID | Test Case | Steps | Expected Result | Status |
|-------|-----------|-------|----------------|--------|
| TC-01 | Login with valid credentials | Enter valid email/password → Click Login | User logs in successfully | Pass |
| TC-02 | Login with invalid credentials | Enter valid email + wrong password → Click Login | Error message appears | Pass |
| TC-03 | Search for a product | Enter product name → Click Search | Relevant products displayed | Pass |
| TC-04 | Add product to cart | Click "Add to Cart" | Product appears in cart | Pass |
| TC-05 | Checkout with login | Add item → Proceed to Checkout | Checkout page loads successfully | Fail |
| TC-06 | Logout | Click Logout | User is logged out | Pass |

<details>
<summary>Notes</summary>
- TC-05 fails due to checkout page error; reported in bug report ALG-001.
</details>

