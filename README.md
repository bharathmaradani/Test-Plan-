
<Center> <h1>Test Plan for Bookshelf Web App
</h1> </center>

## Summary
This document summarizes the scope of React app testing that manages the bookshelf on the web. QA is going to test all the available user test cases. 

## Background
It's a prototype react web app that manages the books on your bookshelf were user should be able to add N number of books to it  without any issues.

## Test Coverage
* Basic  functionality Testing
* Acceptance Testing
* Performance Testing

## Test Environment (Web Browsers)
* Goolge Chrome 
* Internet Explorer
* Mozilla Firefox
* Safari

## Hardware Requirement
* MacBook
* Chromebook
* Windows 

## Bug Triage 
Assign all the bugs to xxx person once filed.

**Note** : I tested the app on two different machines (macbook & Windows ) using chrome browser. I observed two different UI on both the machines. The below bugs are from macBook. 

# Bugs Reported
1. Cancel 'X' button not working in 'Add a new book page'.
 * **Proposed Solution:** It will be good if we have 'X' in circle shape.

2. 'X' button UI looks different from figma image.
* **Proposed Solution:** 'X' UI color shuould be in a different color instead of plane 'X'.

3. Instead of 'Save' button there is a 'Add book' button in 'Add a new book' page.

4. 'Save' button should be disabled if (Title,Authour, Description, Image url)  fields are empty.
* **Proposed Solution:** We can also add 'Cancel' button next to 'Save' button.

5. Description enter text box is small when compared to figma image.

6. (Title, Authour, Description, Image url) enter text fiels font size should be little bigger for a better user experience.

7. Long titles and authors result in misalignment when displayed in bookshelf. 
* **Proposed Solution:** It would be greate if we have a right allignment for very long text 

8. Form not accepting spaces between words in title.

9. If any filed is missing it should throw an error while saving the book 
* **Proposed Solution:** 'Save' button should be disabled until all fields are filled up.

10. Unable to delete the book from bookshelf' page 

11. Delete icon is different from figma page 

12. Description text allignment is not good in 'boookshelf' page.
* **Proposed Solution:** I think it will be good if we limit the description text.

13. In 'Add a new book' page text filed should not take only numbers 

14. Able to see unnecessary 'Book Cover' text with unload image icon on top left of 'bookshelf' page.

15. Unable to add more than 15 books 
* **Proposed Solution:** user should be able to add N number of books to the bookshelf.




  