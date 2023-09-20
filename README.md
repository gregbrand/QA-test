# PINKPANDA EXLOPRER AUTOMATION TEST

### Greetings, young Pandawan!

Welcome to the PinkPanda Online Store's QA Automation Developer interview assignment. We are excited to have you participate in this evaluation process, as we seek to bring on board a talented individual to join our team and contribute to our mission of delivering exceptional makeup products to our customers.
In this assignment, we will assess your skills, creativity, and problem-solving abilities. It's an opportunity for you to showcase your expertise and demonstrate how you can help PinkPanda maintain the highest standards of quality in our online store

## Assignment Details:
- Task: Your task is to design and implement an automated test scenario for a critical feature of our online store. You will receive a detailed description of the feature, including its functionality and acceptance criteria.
- Tools: Feel free to use the automation tools you are most comfortable with. Ensure your solution is well-documented and easily maintainable.

## Requirements
- You are required to use **JavaScript language**
- You are required to use **cypress framework**

## What We're Looking For
- Quality Assurance Skills: We'll be assessing the effectiveness and thoroughness of your testing approach.
- Automation Proficiency: Your ability to create efficient and maintainable automated tests is crucial.
- Problem-solving: We want to see how you handle challenges and solve problems related to testing and automation.
- Documentation: Clear and concise documentation of your work is essential for collaboration and maintenance.

## Assigments

---
### First Assignment:

Test Scenario: Verify Adding Products to Cart and Calculating the Final Price

Test Steps:

- Navigate to the website: https://licila.si.
- In the menu, locate and select the second tab with the text "Znamke."
- Click on the last element in the list with the text "Prikaži vse."
- Select the 15th element (brand) from the list.
- Navigate to page 3.
- Add 3 products to the cart (1st, 5th, 8th on list). If it's out of stock, then skip add in to the basket
- Navigate to page 10.
- Add 6 more products to the cart (random selection, if it's out of stock, then skip add in to the basket).
- Navigate to checkout page, by clicking to basket icon in upper right corner and clicking on button with text "NA BLAGAJNO"
- Calculate the final price by summing the prices of all products in the cart.

Verify if the final price matches the expected total price.

**Expected Outcome**: The final price should match the expected total price.

---

### Second Assignment:

Test Scenario: Verify Product Search and Sorting Functionality

Test Steps:

- Navigate to the website: https://licila.si.
- In the website's search bar, enter a specific product keyword (e.g., "lipstick").
- Click the "Search" or "Find" button/icon.
- Verify that the search results page displays products related to the entered keyword.
- Sort the search results by price in ascending order.
- Capture the prices of the first three products displayed on the sorted results page.
- Verify that the prices of these three products are in ascending order.

**Expected Outcome**: The product search should return relevant results, and the sorting functionality should correctly arrange products by price in ascending order.




