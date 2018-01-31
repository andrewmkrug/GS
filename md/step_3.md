# Step 3
# Use Selenium Fundamentals

+++
# Selenium Fundamentals

- mimics human interaction |
- Uses a few common actions |
- Works with “locators” |

+++

# Common Actions

- get();
- findElement();
- click();
- sendKeys();
- isDisplayed();

+++

# Locator Strategies

- Class
- CSS selectors
- ID
- Link Text
- Partial Link Text
- Tag Name
- XPath

+++

# Good Locators

- unique |
- descriptive |
- unlikely to change |

That means some of these are not great |

+++

# Locator Strategies

- Class
- CSS selectors
- ID
- ~~Link Text~~
- ~~Partial Link Text~~
- ~~Tag Name~~
- XPath

+++

# Locator Strategies
## Start with

- **Class**
- CSS selectors
- **ID**
- ~~Link Text~~
- ~~Partial Link Text~~
- ~~Tag Name~~
- XPath

+++

# Locator Strategies
## Fallback with Care

- **Class**
- __CSS selectors__
- **ID**
- ~~Link Text~~
- ~~Partial Link Text~~
- ~~Tag Name~~
- __XPath__

---?include=md/finding_good_locators.md
