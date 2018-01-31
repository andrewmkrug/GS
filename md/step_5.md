# Step 5
# Write reusable and maintainable test code

+++

# Abstraction!
### Page Objects

+++
# Do I need to Explain Abstraction?


+++

# Let’s look at a page object for login
+++?include=code/java/selenium-workshop-code-examples/04-page-objects/src/test/java/pageobjects/Login.java
@[13-18](Locators, aka most likely to change)
@[20-25](Constructor, might as well be on the page)
@[27-31](Logic for logging in)
+++

insert code for login test

---?include=vanguard/lab_4.md

---
# Can I have some more abstraction?

+++

# Base Page Object

+++
# Benefits

* Global Reuse |
* Readability |
* Insulated from Selenium API changes |

---?include=vanguard/lab_5.md

+++?include=code/java/selenium-workshop-code-examples/05-base-page-object/src/test/java/pageobjects/Base.java

@[11-13](Constructor setting driver as a class level variable)
@[15-17](Wrapping Selenium command, easier to remember)
@[19-21](Making Se command easier to write)
@[23-25](Using new method to make the methods easier)
@[27-29](Making typing easier)
@[31-37](Catching Exception if not found)

+++
# Implementing the Base Page Object

+++?include=code/java/selenium-workshop-code-examples/05-base-page-object/src/test/java/pageobjects/Login.java
@[9-14](Same locators)
@[16-21](Constructor using new method and calling parent constructor)
@[23-27](Refactored method with new wrapped methods)