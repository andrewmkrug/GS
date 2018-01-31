# Bonus Time
+++
# WebDriver

```js
JavascriptExecutor js = (JavascriptExecutor) driver;
js.executeAsyncScript(Script,Arguments);
js.executeScript(Script,Arguments);
```

+++
# WebDriver JS

```js
js.executeScript("arguments[0].scrollIntoView(true);", element);
```

+++
# WebElement

Can also call driver.findElement()
Will look only inside of the found element
Not in entire document

+++

# Cuke

1. Reads Features
2. Finds Matching StepDefs
3. Execute StepDefs
4. If no exceptions: Pass

+++
# Allure

https://ci.qameta.io/job/allure2/job/master/Demo_Report/index.html

+++

lazycoder.io/feedback