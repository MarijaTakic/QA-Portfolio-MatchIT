**﻿Test cases**


Decision table


|Conditions|Rule 1|Rule 2|
| :- | :- | :- |
|Email (T/F)|F|T|
|Output (E/H)|E|H|

**T** - Correct email
**F** - Wrong email
**E** - Error message is displayed
**H** - Home page is displayed


**- Case 1:** Email was wrong. The user is shown an error message.
**- Case 2:** Email was correct. The user navigated to the homepage.



**1\.**

**Test Case ID:** TC1

**Test Case name:** Registration with an invalid email.

**Description:** User cannot log in to the application with an invalid email.


||Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1\.|Open the mobile application “MatchIT”.||Application is opened. Log in screen with email field is displayed.|
|2\.|Enter invalid email in the email field. |123|The provided value is displayed in the email field. Email field is filled in with provided invalid email.|
|3\.|Click the “NASTAVI DALJE” button.||The user stayed on the same page and did not log in. The frame of the email field is red.|

**2\.**

**Test Case ID:** TC2

**Test Case name:** Successful registration

**Description:** Successful user registration to the application with a valid email.


||Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1\.|Open the mobile application “MatchIT”.||Application is opened. Log in screen with email field is displayed.|
|2\.|Enter valid email in the email field. |marijatakic7@gmail.com|Email is filled in the email field.|
|3\.|Click the “NASTAVI DALJE” button.||The user received a pop-up message "Proveri svoj inbox". The user received a link to his entered email address. By clicking on that link, the user can successfully log in to the application. Also, the link that says "Vrati se nazad" appears to the user.|
















**3\.**

**Test Case ID:** TC3

**Test Case name:** Registration with an empty email field.

**Description:** User can’t login to the application with an empty email field.


||Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1\.|Open the mobile application “MatchIT”.||Application is opened. Log in screen with email field is displayed.|
|2\.|Click the “NASTAVI DALJE” button.||The user stayed on the same page and did not log in. Email is required.|




**4\.**

**Test Case ID:** TC4

**Test Case name:** Logout

**Description:** User logout from the application.

**Precondition:**

1. User navigated to the URL.
1. User is logged in and the application is opened. 


||Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1\.|Click the “Profil” tab.||User navigated to the profile tab.|
|2\.|Click the “Odjavi se” button.||User is successfully logged out. Registration page is displayed.|







**5\.**

**Test Case ID:** TC5

**Test Case name:** Adding a certificate

**Description:** Successfully added certificate with all fields validly filled.

**Precondition:**

1. User navigated to the URL.
1. User is logged in and the application is opened. 


||Test Steps|Test Data|Expected Result|
| :- | :- | :- | :- |
|1\.|Click the “Profil” tab.||User navigated to the profile tab.|
|2\.|Click the “Sertifikati” button.||“Sertifikati” page is displayed. "Navedi svoje sertifikate" text is visible. "Dodaj sertifikat" button is active and enabled.|
|3\.|Click the “Dodaj sertifikat” button.||User is redirected to “Dodaj sertifikat”. There are three fields that are visible: "Naziv sertifikata", "Nosilac sertifikata" and "Godina sertifikacije".|
|4\.|Enter valid certificate name in the “Naziv sertifikata” field. |Code Academy by Comtrade|Certificate name field is populated.|
|5\.|Enter valid certificate holder in the “Nosilac sertifikata” field. |Marija Takic|Certificate holder field is populated.|
|6\.|Click on the “Godina sertifikacije” field.||Calendar is displayed.|
|7\.|Enter a valid certification date in the calendar.|09\.05.2023.|The date is visible.|
|8\.|Click the “Potvrdi” button.||The year 2023 is entered in the "Godina sertifikacije" field.|
|9\.|Click the “Sacuvaj” button.||The user has successfully added the certificate. The user is redirected to the "Sertifikati" page. New added certificate is visible: The name of the certificate, the holder of the certificate and the year are visible. In addition, there are icons for editing and deleting certificates.|

