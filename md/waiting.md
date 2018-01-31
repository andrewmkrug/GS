# Waiting

+++

- Thread.sleep()
- Implicit Waits
- Explicit Waits
- Fluent Waits

+++

# Aren't we developers?

+++

- ~~Thread.sleep()~~
- Implicit Waits
- Explicit Waits
- Fluent Waits

+++
# Implicit Wait

- Specify an amount of time (@ test setup) |
- Selenium will retry every action that fails every 250 ms until: |
  - Action is Completed |
  - TimeoutException |
  
+++
# Explicit Wait

- Specify an amount of time and action  |
    - Action includes a locator |
- Selenium will retry every 250 ms until: |
    - Action is Completed |
    - TimeoutException |
    
+++
# Fluent Wait
- Specify an amount of time, action and retry period |
    - Action includes a locator |
- Selenium will retry every period until: |
    - Action is Completed |
    - TimeoutException |
+++
# What's the Diff

Implicit - Global |
Explicit - Per Element |
Fluent - Explicit with custom retry period |

+++
# Using Implicit and Explicit Together

![Jim stackoverflow response]()

+++

- ~~Thread.sleep()~~
- ~~Implicit Waits~~
- Explicit Waits
- Fluent Waits

+++
# How often do you want to customize retry period?

+++
- ~~Thread.sleep()~~
- ~~Implicit Waits~~
- Explicit Waits
- ~~Fluent Waits~~