# test-teach-away
Test menu items for teachaway website

I have used Action class to test the menu item for TeachAway website. As menu opens with mouse over, Action class in Selenium is used to emulate complex user gestures like mouse over, double click etc. I have verified that each menu item is enabled on the UI. If any menu item is not enabled or displayed, error will be shown and the assertion will fail. This will indicate that UI is not working as expected and test will stop. 

I have Added all tests in TeachAwayTest.java file. I have verified all level 1 and level 2 menu items and verified one menu for level3 as well.

For Future use- I have created a TDD framework to support the automation above, and created the page object classes. This framework will run as TestNG. 

Benefits:

All locators can be defined in one place
We can create one single method where different xpath can be passed which will avoid the duplication of code
It will also help in code maintenance and improve the code readability.


