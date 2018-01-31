# Lab 3
## Your first assertion

+++
# How to Find an Assertion

1. Login
2. Inspect the page
3. Find a locator
4. Verify it
5. Add it to the test
+++?include=code/java/selenium-workshop-code-examples/03-your-first-test-assertion/src/test/java/tests/TestLogin.java
@[33-34](The assertion)
@[35-36](A Bad Locator for the Flash Message)

+++
# Did any one still get a fail?
org.openqa.selenium.NoSuchElementException:
Unable to locate element:
{"method":"css selector","selector":".flash.error"}

+++
# Race Condition

Selenium and Javascript both run after the browser returns ```DOM.ready();```
+++
# Most common exceptions:  
* NoSuchElement |
* StaleElementReferenceError |

+++
# NoSuchElement

Element not found at time of execution.

+++
# StaleElementReferenceError

**If** the browser returns a ```DOM.ready()```
**Then** all previously found elements are no longer valid


