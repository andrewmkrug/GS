# Getting Started with Selenium

## Andrew Krug

---?include=md/about-me.md

---?include=md/selenium-intro.md

---?include=md/selenium-overview.md

---?include=md/step_1.md

---?include=md/step_2.md

+++ 

# Good News, Everybody!

+++

# We are going to use Java!

---?include=md/vanguard/computer_setup.md

---?include=md/step_3.md

---?include=md/vanguard/lab_1.md

---?include=md/step_4.md
+++?include=code/java/selenium-workshop-code-examples/02-your-first-test/src/test/java/tests/TestLogin.java

@[30-33](Go package main for executable command)

---?include=md/vanguard/lab_2.md

---?include=md/vanguard/lab_3.md

---?include=md/step_5.md
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
---?include=md/step_6.md
+++?include=waiting.md
---?include=md/step_7.md

