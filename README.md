# SEB Selenium Assignment

This project is for educational purposes only. Pull request are welcome! Thank you for your cooperation!

## Requirements
- Google Chrome Version 94 (if you are using different chrome version you need download and replace chromedriver.exe file inside driver folder) download link for drivers (https://chromedriver.chromium.org/downloads)
- Java SE Development Kit ([Download]( https://www.oracle.com/java/technologies/javase-jdk15-downloads.html))
- IntelliJ IDEA ([Download]( https://www.jetbrains.com/idea/download/#section=windows))
- Eclipse IDE ([Download]( https://www.eclipse.org/downloads/))
- Another IDE with Java support

## Setup
I prefer Eclipse IDE so example is done using Eclipse
- Install Eclipse IDE
- Once launched Eclipse IDE install TestNG Plugin
- Tutorial: https://www.youtube.com/watch?v=yAzLc0xz0l4

## Usage
- Download folder or clone using GIT
- Import Maven project in Eclipse
- Run ```testng.xml``` file to start test. (Run As TestNG Suite)
- Tutorial: https://vimeo.com/489454435

## Additional comments:
- Add/Remove, inside for loop user can choose how many buttons will be added, in second loop number must be the same in order to delete all added buttons.
- Checkboxes, number of checkboxes are automatically counted, check and uncheck functionality will be applied depending on number of checkboxes. Assert added to both checked and unchecked boxes. Without thread sleep runs to fast to notice changes.
- Dropdown, chosen option 1, Assert checks if option indeed was chosen, select value printed in console.
- Dynamic loading, test waits until element is visible, as soon as it is visible assert is checked and tests continues.
- Hower, chosen image printed in console, assert checks if value is visible during hover effect.
- Input, in for loop user can chose how many random numbers will be checked. Numbers are generated from users chosen min and max values, all used values are printed in console.
- ContextMenu, right-click functionality checked, alert automatically closed, console print out if alert was shown.



### Authors: [Vaidas Pocius]( https://github.com/Vaidas393)
