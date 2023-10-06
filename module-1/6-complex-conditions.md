# Complex conditions

Problems that focus on using complex conditions (combining multiple conditions using logical operators like `&&`, `||`, and `!`):

---

**1) Design a function that checks if a given number is both even and greater than 10. If both conditions are met, return "Even and Greater than 10", otherwise return "Condition not satisfied".**

Example Input: 14
Example Output: "Even and Greater than 10"

<details>
  <summary>Hint</summary>
  Hint: Use the modulus operator to check for evenness and combine it with a condition to check if the number is greater than 10.
</details>

Follow-up: Can you modify the function to also check if the number is less than 50?

Example Input: 48
Example Output: "Even, Greater than 10, and Less than 50"

---

**2) Create a function that accepts two boolean parameters: `isRaining` and `hasUmbrella`. If it's raining and the person has no umbrella, return "Stay Inside!". If it's raining and the person has an umbrella, or if it's not raining, return "Good to go!".**

Example Input: true, false
Example Output: "Stay Inside!"

<details>
  <summary>Hint</summary>
  Hint: Combine conditions using logical operators to check both scenarios where the person should stay inside or go out.
</details>

Follow-up: Add another parameter `likesRain`. If the person likes rain and doesn't have an umbrella, suggest they enjoy the rain instead.

Example Input: true, false, true
Example Output: "Enjoy the rain!"

---

**3) Design a function that accepts three parameters representing the lengths of the sides of a triangle. The function should determine if it's an equilateral, isosceles, or scalene triangle.**

Example Input: 5, 5, 5
Example Output: "Equilateral"

<details>
  <summary>Hint</summary>
  Hint: Start by checking if all three sides are equal. If not, determine if any two sides are equal for an isosceles triangle. If neither condition is met, it's a scalene triangle.
</details>

Follow-up: Can the function also determine if it's a right triangle based on the Pythagorean theorem?

Example Input: 3, 4, 5
Example Output: "Scalene and a Right triangle"

---

Certainly! Here are three more problems that utilize complex conditions:

---

**4) Write a function that checks if a person is eligible to vote. To be eligible, a person needs to be above 18 years of age and must be a registered voter. The function should accept age and a boolean `isRegistered` as parameters.**

Example Input: 20, true
Example Output: "Eligible to vote"

<details>
  <summary>Hint</summary>
  Hint: Combine conditions to check both age and registration status for eligibility.
</details>

Follow-up: Can the function also inform if the person is eligible to drive, considering they can drive if they are above 16?

Example Input: 17, false
Example Output: "Not eligible to vote, but eligible to drive"

---

**5) Create a function that determines if a shop should open. The shop opens if it's a weekday and it's not a holiday. The function should accept a day of the week and a boolean `isHoliday` as parameters.**

Example Input: "Tuesday", false
Example Output: "Shop opens"

<details>
  <summary>Hint</summary>
  Hint: Check if the day is a weekday and combine this condition with the holiday status.
</details>

Follow-up: If the shop remains closed, can the function suggest a rest day for the owner?

Example Input: "Sunday", false
Example Output: "Shop remains closed. Have a restful day!"

---

**6) Design a function that accepts two parameters: `temperature` and `weatherCondition`. The function should determine the type of clothing to wear. If the temperature is below 10°C and the weather is rainy, suggest "Wear a warm coat and carry an umbrella". If the temperature is above 20°C and sunny, suggest "Wear light clothing and put on sunscreen". For all other conditions, suggest "Dress comfortably".**

Example Input: 8, "rainy"
Example Output: "Wear a warm coat and carry an umbrella"

<details>
  <summary>Hint</summary>
  Hint: Use a combination of conditions to determine the appropriate clothing suggestion based on the temperature and weather condition.
</details>

Follow-up: If the weather condition is "snowy", irrespective of temperature, can the function suggest "Wear boots and a heavy jacket"?

Example Input: 2, "snowy"
Example Output: "Wear boots and a heavy jacket"

---