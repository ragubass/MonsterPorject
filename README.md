# MonsterPorject

Test Cases

**Feature**: Carousels / sliders / horizontal scrollers Elements check

**Scenario**: Verify the home page loaded successfully

  Given Enter the url
  
  Then Verify home page loaded successfully.

**Scenario**: Verify Carousels / sliders / horizontal scrollers displayed

  Given Enter the url https://www.mall.cz/
  
  When Scroll down home page to Carousels / sliders / horizontal
  
  Then Carousels / sliders / horizontal displayed

**Scenario**: Get the carousel count and verify the count is greater than 15 elements

  Given Go to the carousel
  
  When Get carousel count
  
  And Verify the carousel count is greater than 15 elements
  
  Then Display pass/fail

**Scenario**: Compare the elements and check whether the elements are unique

  Given Go to carouse
  
  When Get carousel element text
  
  And Store the carousel element into an array lists
  
  Then Compare the lists and verify the elemetns are unique.
