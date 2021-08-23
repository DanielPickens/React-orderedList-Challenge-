# React-orderedList-Challenge-
An sorted ordered list alphabetically placed with specific input elements according to array of specificactions


The Challenge
Let's write a little component in React, OrderedList, which implements an alphabetically sorted list. The component will include a button to enable the user to sort either in ascending or descending order and a second button to permit the list to be cleared.
Your component should render specific elements according to the following specifications:
An <input /> element which the user can use to add items to the list. This input field should listen for Enter keydown events (the test suite triggers the onKeyDown event handler specifically) to add the current contents (if nonempty) to the list. After adding an item, the input box should be cleared.
A <button> element which the user can click to change the direction of the sort. Initially, the button should display text such as the ⬇️ emoji or the text down. When changed to a descending sort, the button should change to a ⬆️ emoji (or text such as up). 
A <button> element which the user can click to clear the list as well as any contents in the input box (essentially reverting to the component's default state). Use any text you'd like for this button.
A <ul> element, which should contain a series of <li> elements that represent the sorted list contents.
There is no predetermined correct answer for style and CSS. Your solution need not look like the demo below but it should demonstrate understanding of basic CSS and user experience principles.
