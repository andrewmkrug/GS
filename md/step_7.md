# Step 7
# Prep for Use
### By more than you

+++
# Core Features

1. Simple organizational structure |
2. Central setup and teardown |
3. Configurable at run-time (with sensible defaults) |
4. Reporting & Logging |
5. Parallelization |
6. Dynamic Test Segmentation |

+++
# Folder Structure
![folder structure for selenium](assests/imgage/folder_structure.png)

+++
# Central Setup & Teardown

+++
# Simple Config
## Sensible Defaults

+++
# Import when needed

+++?code=code/java/selenium-workshop-code-examples/07-framework/src/test/java/tests/Config.java

+++?include=code/java/selenium-workshop-code-examples/07-framework/src/test/java/pageobjects/Base.java
@[19-25](Sweet updated method)
@[20-21](If full url then navigate directly)
@[22-23](Else append parameter to baseUrl)