# Combined if else
---

**1) Design a function that accepts a number. If the number is below 50, classify it as "Low". If it's between 50 and 100, classify it as "Medium". If it's over 100, check if it's even or odd and return "High Even" or "High Odd".**

Example Input: 120
Example Output: "High Even"

<details>
  <summary>Hint</summary>
  Hint: First categorize the number based on its value, then add an additional check for numbers over 100 to determine if they are even or odd.
</details>

Follow-up: Can you also check if numbers below 50 are prime or not?

Example Input: 47
Example Output: "Low Prime"

---

**2) Create a function that accepts an age and a boolean value representing whether the person has a driving license. If the age is below 18, return "Too young to drive". If they are 18 and above but don't have a license, return "Eligible but lacks a license". If they are 18 and above and have a license, return "Eligible and has a license".**

Example Input: 20, true
Example Output: "Eligible and has a license"

<details>
  <summary>Hint</summary>
  Hint: Begin with an age check, then nest a condition based on the license boolean.
</details>

Follow-up: Add another condition where if someone is above 60 and has a license, they're advised to take a medical check-up.

Example Input: 65, true
Example Output: "Eligible and has a license but advised to take a medical check-up"

---

**3) Write a function that checks a given temperature and whether it's raining. If the temperature is above 30°C and it's not raining, return "Summer Day". If it's raining and temperature is between 20°C to 30°C, return "Rainy Day". If the temperature is below 20°C, regardless of rain, return "Cold Day".**

Example Input: 25°C, true
Example Output: "Rainy Day"

<details>
  <summary>Hint</summary>
  Hint: Begin with a temperature check, then add a nested condition to account for rain.
</details>

Follow-up: Can the function also provide advice on the type of clothing to wear?

Example Input: 15°C, false
Example Output: "Cold Day - Wear a jacket!"

---