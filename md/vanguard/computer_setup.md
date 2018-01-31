# Fun Time!

+++

## Setup your Machines
(see handout)

If you RDP into your own machine, no promises that it will work.

Once you run your tests and one of them passes don't continue

+++

# How to get Chrome to work

```java
ChromeOptions options = new ChromeOptions();
options.addArguments("--disable-extensions");
options.setExperimentalOption("useAutomationExtension", false);
```

@[3](Add this line)

+++
# How to get Chrome to work

```xml
<parent>
    <groupId>com.vanguard</groupId>
    <artifactId>selenium-parent</artifactId>
    <version>3.3.0-SNAPSHOT</version>
</parent>
```

@[4](Update this line)

+++
# Download 2.34 Chromedriver

![unzip and copy to test/src/resources](unzip_to_resources.gif)

