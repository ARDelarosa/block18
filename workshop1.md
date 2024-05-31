Unit Tests
1. A function called "multiplication" that returns the product of the two numbers. 

Expect multiplication(2, 5) to be (10);

Expect multiplication(-5, 0) to be (0);

Expect multiplication(2.3, 0.05) to be (0.115);

Expect multiplication("$", 1) to be error.

2. A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.

Expect concatOdds([2, 4, 6], [6, 8, 10]) to be  ([]);

Expect concatOdds([-1, -2, -3], [-4, -5, -6]) to be ([-1, -3, -5]);

Expect concatOdds([2, b, 0,], [6, 7a, 9c]) to be an undefined. 

Functional Tests
1. A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.

When choosing to create an account, will it direct him to account creation page?

If the user leaves the input box blank will it return a error msg, same as if he puts an incorrect passoword creation syntax, will it return as invalid password to be made.

After creating an account or logging in, will it redirect the user back to their check out cart?

When choosing login-in, will the user be prompt to put in his/her user id and password?

If the user prompts to continue as "just a customer" will it direct him to checkout page correctly?

In the checkout page, will the address to submit stop the user if all the user input boxes are not filled out?

If the user for example puts in the wrong zipcode format, will there be an error msg returned?

Will all options for payments direct the user to the correct page, or output a data box so the user can input payment form?

If the user puts in the wrong card number or etc, will an error msg returned promptly?

When the user finishes and clicks submit, will everything go through correctly and return a page that tells the user thank you and gives them their order number?

