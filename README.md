# Manual-testing
Bug Report: Unable to Send Video Files in Group Chats on Whatsapp Mobile Application

Bug Description:
Users are unable to send video files in group chats on the Whatsapp mobile application. However, this workflow is working fine in private chat. When attempting to send a video file in a group chat, the user receives an error message stating that the video cannot be sent. This issue has been observed on both Android and iOS versions of the Whatsapp mobile application.

Steps to Reproduce:

1. Open the Whatsapp mobile application.
2. Create a new group chat or select an existing group chat.
3. Tap on the "Attach" icon.
4. Select "Gallery" and choose a video file.
5. Tap on the "Send" icon.
6. Observe the error message stating that the video cannot be sent.
Expected Behavior:
The video file should be sent successfully in the group chat.

Actual Behavior:
The user receives an error message stating that the video cannot be sent in the group chat.

Impact:
This bug prevents users from sharing video files in group chats on the Whatsapp mobile application, which is a major feature of the application. It can cause inconvenience to users who want to share videos with multiple recipients simultaneously.

Workaround:
Currently, there is no known workaround for this issue. However, users can still share videos in private chat on the Whatsapp mobile application.

Reproducibility:
The issue is reproducible consistently on multiple devices running the latest versions of the Whatsapp mobile application on Android and iOS.

Additional Information:
This bug was first observed on March 31st, 2023. There have been no recent updates to the Whatsapp mobile application that may have caused this issue. All other features of the application appear to be working fine.

2.Bug Report: Submit Button Not Working on Login Page

Bug Description:
The submit button on the login page is not working. When the user enters their login credentials and clicks on the "submit" button, nothing happens. The user is not logged in to the system, nor are any error messages displayed. This issue has been observed on both desktop and mobile versions of the login page.

Steps to Reproduce:

1. Open the login page.
2. Enter valid login credentials.
3. Click on the "submit" button.
4. Observe that nothing happens.
Expected Behavior:After clicking on the "submit" button, the user should be logged in to the system if the entered credentials are correct. If the credentials are incorrect, an error message should be displayed.

Actual Behavior:
After clicking on the "submit" button, nothing happens. The user is not logged in to the system, nor are any error messages displayed.

Impact:
This bug prevents users from logging in to the system using the login page, which is a major feature of the system. It can cause inconvenience to users who need to access the system to perform their tasks.

Workaround:
Currently, there is no known workaround for this issue.

Reproducibility:
The issue is reproducible consistently on multiple devices and browsers.

Additional Information:
This bug was first observed on April 1st, 2023. There have been no recent updates to the login page or the system that may have caused this issue. All other features of the system appear to be working fine.


3.Bug Report: Failure to Load Chat Messages in WhatsApp

Bug Description:
Users are experiencing a failure to load chat messages in WhatsApp. When attempting to open a chat thread, the application is not displaying the messages in that chat thread. Instead, the screen remains blank, and the user is unable to view any messages or send new messages in that thread. This issue has been observed on both Android and iOS versions of the WhatsApp application.

Steps to Reproduce:

1. Open the WhatsApp application.
2. Navigate to a chat thread that contains messages.
3. Observe that the messages do not load on the screen, and the screen remains blank.
Expected Behavior:
The messages in the chat thread should load on the screen, and the user should be able to view and send new messages in that thread.

Actual Behavior:
The messages in the chat thread are not loading on the screen, and the screen remains blank. The user is unable to view or send new messages in that thread.

Impact:
This bug prevents users from accessing their chat messages in WhatsApp, which is a major feature of the application. It can cause inconvenience to users who need to access their messages to communicate with their contacts.

Workaround:
Currently, there is no known workaround for this issue.

Reproducibility:
The issue is reproducible consistently on multiple devices running the latest versions of the WhatsApp application on Android and iOS.

Additional Information:
This bug was first observed on April 1st, 2023. There have been no recent updates to the WhatsApp application that may have caused this issue. All other features of the application appear to be working fine.

4.Write a few testcases for booking tickers in redbus.

1.Test case name: Successful booking of a single ticket for a specific date and route
Preconditions: User has a valid account, desired route and travel date are available for booking.
Steps:
Login to Redbus account
Search for desired route and travel date
Select desired bus and seat(s)
Enter passenger details
Proceed to payment and complete the transaction
Expected result: A confirmation message should be displayed, and the ticket should be successfully booked for the selected route and travel date.

2.Test case name: Attempting to book a ticket for a route and date that is not available
Preconditions: User has a valid account, the desired route and travel date are not available for booking.
Steps:
Login to Redbus account
Search for an unavailable route and travel date
Attempt to book a ticket for that route and travel date
Expected result: An error message should be displayed, indicating that the selected route and travel date are not available for booking.

3.Test case name: Cancelling a booked ticket
Preconditions: User has a valid account, a ticket is booked.
Steps:
Login to Redbus account
Navigate to the booked tickets section
Select the ticket to be cancelled
Click on the cancel button and confirm the cancellation
Expected result: A confirmation message should be displayed, and the cancelled ticket should no longer appear in the booked tickets section.

4.Test case name: Attempting to book a ticket with invalid passenger details
Preconditions: User has a valid account, the desired route and travel date are available for booking.
Steps:
Login to Redbus account
Search for desired route and travel date
Select desired bus and seat(s)
Enter invalid passenger details (e.g. invalid name, age, gender, etc.)
Proceed to payment and complete the transaction
Expected result: An error message should be displayed, indicating that the passenger details entered are invalid.

5.Test case name: Attempting to book a ticket without selecting a seat
Preconditions: User has a valid account, the desired route and travel date are available for booking.
Steps:
Login to Redbus account
Search for desired route and travel date
Select desired bus without selecting a seat
Attempt to proceed to payment
Expected result: An error message should be displayed, indicating that the user must select a seat before proceeding to payment.

5. Bug Report: Profile Picture Not Updated in WhatsApp

Bug Description:
Users are experiencing an issue where their profile picture is not being updated in WhatsApp. When attempting to change the profile picture, the application does not display the updated picture in the user's profile. Instead, the previous profile picture is still displayed. This issue has been observed on both Android and iOS versions of the WhatsApp application.

Steps to Reproduce:

1. Open the WhatsApp application.
2. Navigate to the user's profile section.
3. Click on the profile picture and select a new picture.
4. Crop and save the new picture.
5. Observe that the profile picture is not updated and the previous picture is still displayed.

Expected Behavior:
The new profile picture should be updated and displayed in the user's profile section.

Actual Behavior:
The new profile picture is not updated, and the previous picture is still displayed in the user's profile section.

Impact:
This bug can cause confusion among users who are trying to update their profile picture. It may also prevent users from accurately representing themselves in their WhatsApp profile.

Workaround:
Currently, there is no known workaround for this issue.

Reproducibility:
The issue is reproducible consistently on multiple devices running the latest versions of the WhatsApp application on Android and iOS.


6. Write any 5 Negative testcases. 

1. Invalid input: Entering invalid input into a field, such as entering text into a field that only accepts numbers or special characters into a field that only accepts letters. The application should reject the invalid input and display an error message.

2. Missing input: Attempting to submit a form or complete a transaction without filling in required fields. The application should prompt the user to fill in the missing fields and prevent the transaction from completing until all required information is provided.

3. Unauthorized access: Attempting to access a feature or resource without proper authentication or authorization. The application should prevent access and display an error message indicating that the user is not authorized to access the feature or resource.

4. Boundary conditions: Testing the limits of input ranges or processing limits, such as entering a number that is too large or too small, or attempting to perform an action that exceeds the system's processing capabilities. The application should handle these boundary conditions gracefully, such as displaying an error message or preventing the action from completing.

5. Compatibility: Testing the application on devices or browsers that are not compatible with the application. The application should be tested on a range of devices and browsers to ensure that it works properly and displays correctly. If the application is not compatible with a particular device or browser, it should display an error message or provide alternative options for accessing the application.

7.Write a few test cases for the IRCTC Web Application.
1. Login functionality: Verify that the user can log in to the application using valid credentials, and that an error message is displayed if the user enters invalid credentials.

2. Search functionality: Verify that the user can search for trains by entering valid source and destination stations, and that the application displays a list of available trains along with their schedules and fares.

3. Ticket booking functionality: Verify that the user can book a ticket by selecting a train, entering passenger details, and making payment. Verify that the application displays a confirmation page with the ticket details after the booking is complete.

4. Cancellation functionality: Verify that the user can cancel a booked ticket and receive a refund if the cancellation is made within the specified time limit. Verify that the application displays a confirmation page and updates the user's booking history after the cancellation is complete.

5.Seat availability functionality: Verify that the user can check the availability of seats on a particular train by entering the source, destination, and date of travel. Verify that the application displays the number of available seats and their fares.

6. Payment gateway integration: Verify that the payment gateway is integrated properly and that the user can make payment using various payment modes, such as credit/debit cards, net banking, and mobile wallets. Verify that the application displays a confirmation page after the payment is complete.

7. Security: Verify that the application is secure and that the user's personal and financial information is protected. Verify that the application uses HTTPS protocol and that all sensitive data is encrypted.

8. Performance: Verify that the application performs well under heavy load and that it can handle a large number of concurrent users without crashing or slowing down. Verify that the application responds quickly to user actions and that the pages load fast.

9. Accessibility: Verify that the application is accessible to users with disabilities and that it conforms to WCAG (Web Content Accessibility Guidelines) standards. Verify that the application can be used with assistive technologies such as screen readers and voice recognition software.

10. Usability: Verify that the application is user-friendly and easy to use. Verify that the user can navigate the application easily and that the pages are well-designed with clear and concise information.




8.Write a few test cases for the SpiceJet Web Application.

1. Login functionality: Verify that the user can log in to the application using valid credentials, and that an error message is displayed if the user enters invalid credentials.

2. Flight booking functionality: Verify that the user can book a flight by selecting the source and destination airports, travel dates, and number of passengers. Verify that the application displays a list of available flights along with their schedules and fares.

3. Seat selection functionality: Verify that the user can select seats during the booking process and that the application displays a confirmation page with the selected seats.

4. Meal selection functionality: Verify that the user can select meals during the booking process and that the application displays a confirmation page with the selected meals.

5. Baggage selection functionality: Verify that the user can select baggage during the booking process and that the application displays a confirmation page with the selected baggage.

6. Payment gateway integration: Verify that the payment gateway is integrated properly and that the user can make payment using various payment modes, such as credit/debit cards, net banking, and mobile wallets. Verify that the application displays a confirmation page after the payment is complete.

7. Flight cancellation functionality: Verify that the user can cancel a booked flight and receive a refund if the cancellation is made within the specified time limit. Verify that the application displays a confirmation page and updates the user's booking history after the cancellation is complete.

8. Flight rescheduling functionality: Verify that the user can reschedule a booked flight and that the application displays a confirmation page with the new flight details.

9. Flight status functionality: Verify that the user can check the status of a flight by entering the flight number or the source and destination airports. Verify that the application displays the status of the flight along with any updates or delays.

10. Accessibility: Verify that the application is accessible to users with disabilities and that it conforms to WCAG (Web Content Accessibility Guidelines) standards. Verify that the application can be used with assistive technologies such as screen readers and voice recognition software.




9.Create 10 test cases for amazon mobile view.

1.Verify that the home page of Amazon mobile view is displayed correctly, including the header, footer, and main content area.

2.Verify that the search functionality works properly, allowing the user to search for products by keyword, category, or other criteria.

3.Verify that the product detail page is displayed correctly, including all relevant information such as product name, image, description, price, and customer reviews.

4.Verify that the user can add products to their cart and proceed to checkout without any issues.

5.Verify that the checkout process works properly, allowing the user to enter shipping and billing information, select a payment method, and complete the purchase.

6.Verify that the user can view their order history and track the status of their orders.

7.Verify that the user can leave product reviews and ratings, and that these are displayed correctly on the product detail page.

8.Verify that the user can access their account settings and update their personal information, shipping addresses, and payment methods.

9.Verify that the user can access customer support and contact Amazon for help with any issues or questions they may have.

10.Verify that the mobile view of Amazon is responsive and works well on a variety of devices, including smartphones and tablets with different screen sizes and resolutions.

10.Create 10 Bug report for amazon website and mobile view.

1. Bug Report: Unable to add products to the cart on the Amazon website. When attempting to add a product to the cart, the website displays an error message stating that the product is no longer available.

2. Bug Report: Broken link on the Amazon mobile view. When clicking on a link to a product category, the website displays a 404 error page instead of the category page.

3. Bug Report: Slow page load times on the Amazon website. Pages take several seconds to load, making it difficult to navigate the site quickly.

4. Bug Report: Incorrect prices displayed on the Amazon mobile view. Prices for some products are shown as much higher or lower than the actual price.

5. Bug Report: Inconsistent search results on the Amazon website. When searching for products, some results are missing or appear in a different order than expected.

6. Bug Report: Payment processing error on the Amazon mobile view. After entering payment information and clicking "submit," the website displays an error message and does not process the payment.

7. Bug Report: Broken image links on the Amazon website. Images for some products are missing or not displayed correctly, making it difficult to view the product.

8. Bug Report: Incorrect product descriptions on the Amazon mobile view. Descriptions for some products are incorrect or incomplete, making it difficult for customers to make informed purchasing decisions.

9. Bug Report: Inconsistent font sizes on the Amazon website. Font sizes vary throughout the site, making it difficult to read some text on smaller screens.

10. Bug Report: Broken login functionality on the Amazon mobile view. When attempting to log in to the website, the login page does not load properly and prevents users from accessing their account.



















