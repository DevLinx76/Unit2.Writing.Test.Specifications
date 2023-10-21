# Test Specifications

## Unit Tests

### Multiplication Function

1. **Expect** `multiplication(3, 4)` **to be** `12`.
2. **Expect** `multiplication(0, 4)` **to be** `0`.
3. **Expect** `multiplication(-3, 4)` **to be** `-12`.
4. **Expect** `multiplication(3, 0)` **to be** `0`.
5. **Expect** `multiplication(0, 0)` **to be** `0`.
6. **Expect** `multiplication(-3, -4)` **to be** `12`.

### concatOdds Function

1. **Expect** `concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1])` **to be** `[-1, 1, 3, 9, 15]`.
2. **Expect** `concatOdds([], [1, 2, 3, 4])` **to be** `[1, 3]`.
3. **Expect** `concatOdds([2, 4, 6], [8, 10, 12])` **to be** `[]` (no odd numbers).
4. **Expect** `concatOdds([5, 5, 5], [5, 5, 5])` **to be** `[5, 5, 5, 5, 5, 5]` (repeated numbers are included).
5. **Expect** `concatOdds([1, 3, 5], [])` **to be** `[1, 3, 5]`.

## Functional Tests: Shopping Cart Checkout

1. When a user clicks on the "Checkout" button with items in the cart, they should be taken to the checkout page.
2. When a user clicks on the "Checkout" button with no items in the cart, they should see a message indicating the cart is empty.
3. When a user checks out as a guest, they should be asked if they want to create an account or log in.
4. When a user chooses to check out as a guest and proceeds, they should be able to finalize the purchase without an account.
5. When a user is logged in and clicks on the "Checkout" button, their saved information should be auto-populated.
6. At the end of the checkout process, the user should receive a confirmation of the purchase.

