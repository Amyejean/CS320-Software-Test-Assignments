Reflection
How can I ensure that my code, program, or software is functional and secure?

I make sure my software is functional by writing unit tests that directly map to the requirements and by running those tests consistently after changes. I focus on testing both “happy paths” (valid inputs) and edge cases (nulls, max lengths, invalid dates, duplicates) so I can catch failures early instead of discovering them later. To keep my code more secure, I validate inputs, enforce constraints in constructors/services, and avoid letting invalid data get stored in the system. I also try to keep methods simple and readable, because clean code is easier to test, review, and maintain—which helps prevent bugs and security issues.

How do I interpret user needs and incorporate them into a program?

I start by turning user needs into clear requirements and rules I can verify, like “ID cannot be null,” “field length max,” or “date can’t be in the past.” Then I translate those requirements into program behavior using validation logic in the object and service layers. After that, I write tests that prove each requirement is met and that the system reacts correctly when requirements are violated (like throwing an exception or rejecting an update). This helps me stay aligned to what the user asked for, instead of coding based on assumptions.

How do I approach designing software?

I design software by breaking the problem into smaller parts with clear responsibilities (like separate classes for objects vs. services). I keep the object classes focused on storing data and enforcing rules, and I use service classes to manage actions like add, update, and delete. I try to design with maintainability in mind—simple methods, consistent naming, and logic that’s easy to test. Once the structure is in place, I iterate by using test results and feedback to improve the design and make the code more reliable.
