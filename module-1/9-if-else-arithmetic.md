# if-else statements with arithmetic operations

---

**1) Create a function that calculates the discount for a given price. If the price is above $100, apply a 10% discount. If it's between $50 and $100, apply a 5% discount. For prices below $50, there's no discount.**

Example Input: $120
Example Output: "Your discount is $12."

<details>
  <summary>Hint</summary>
  Hint: Use conditional statements to determine which percentage to apply and then calculate the discount amount.
</details>

Follow-up: Can the function also return the final price after the discount?

Example Input: $55
Example Output: "Your discount is $2.75. Final price is $52.25."

---

**2) Design a function that calculates the area of a circle based on its radius. If the radius is negative or zero, return an error message.**

Example Input: 7
Example Output: "The area of the circle is 153.94."

<details>
  <summary>Hint</summary>
  Hint: Use the formula \( \pi r^2 \) for area. Consider using the built-in `Math.PI`.
</details>

Follow-up: Can the function also calculate the circumference?

Example Input: 3
Example Output: "The area of the circle is 28.27. The circumference is 18.85."

---

**3) Write a function that calculates the number of days between two given years. Consider every year as having 365 days but include an additional day for each leap year in between.**

Example Input: 2000, 2004
Example Output: "The number of days between the years is 1826."

<details>
  <summary>Hint</summary>
  Hint: Consider using a loop to iterate through each year and add either 365 or 366 days based on if it's a leap year.
</details>

Follow-up: Can the function account for cases where the start year is after the end year by reversing the order?

Example Input: 2025, 2020
Example Output: "The number of days between the years is 1826."

---

**4) Design a function that calculates and returns the sum of all even numbers up to a given number.**

Example Input: 10
Example Output: "The sum of even numbers up to 10 is 30."

<details>
  <summary>Hint</summary>
  Hint: Use a loop to iterate through each number up to the given number. Check if it's even before adding to the total.
</details>

Follow-up: Can the function also calculate the average of these even numbers?

Example Input: 6
Example Output: "The sum of even numbers up to 6 is 12. The average is 4."

---