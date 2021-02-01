# Shopping Basket

- This application is to emulate an online store with multiple items.
- Items added to the cart adjust the total.
- The total is adjusted when certain discounts are applied.

### Challenge

Given a store with three products — Milk, Bread & Jam — create a solution that can calculate the total amount due based on the supplied inputs.

#### Products

- Jam - $5.91
- Milk - $3.13
- Bread - $2.19

#### Discounts

- Jam when purchased with Bread is 15% off.
- Milk is half price when purchased with another bottle of milk.
- Jam is free if the customer purchases 5 units.

#### Expectations

- The application should input the store items from file.
- The output should be provided to console.
- TypeScript should be used as the language of choice.

#### Example Inputs & Outputs

** Example 1 **

Input:

```
JAM
JAM
MILK
JAM
```

Output:

```
$20.86
```

** Example 2 **

Input:

```
MILK
MILK
JAM
BREAD
```

Output:

```
$11.91
```
