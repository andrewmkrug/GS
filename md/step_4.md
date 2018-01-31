# Step 3
# Write Good Tests

+++

# How do you determine if a test is good?

+++

# Good Test Criteria

- Write for BDD or xUnit test framework |
- Test one thing (atomic) |
- Each test can be run independently (autonomous) |
- Anyone can understand what it is doing |
- Group similar tests together |

+++

# Login Example
* Visit the login form |
* Find the login form’s username field and input text |
* Find the login form’s password field and input text |
* Find the submit button and click it |

+++
# Login Example
* **Visit** the login form
* **Find** the login form’s username field and **input** text
* **Find** the login form’s password field and **input** text
* **Find** the submit button and **click** it

+++?code=code/java/selenium-workshop-code-examples/02-your-first-test/src/test/java/tests/TestLogin.java&title=Your First Test!

@[30-33](Go package main for executable command)

