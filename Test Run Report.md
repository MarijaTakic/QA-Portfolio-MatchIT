**Test Run Report**


**Project Information**

It is an application for employment in the IT sector. Match IT is a platform that makes it easier for candidates to search for a job. It is also known as "Tinder for employment".

**Project Name:** “MatchIt” mobile application.

**Team assigned:** QA member Marija Takic.

**Document overview**

**Scope:**

Tested:

Mobile app:

- “Profil” (Tehnologije, Iskustvo, Benefiti, Sertifikati, Veštine i bedževi)
- “Početna”
- “Mečevi”

Web app:

- “Oglasi” page
- MatChat
- Matches

Non tested:

Mobile app:

- “Profil” (Osnovni podaci, Plata i način rada, Edukacija)

Web app:

- “Dodaj oglas”
- Profil kompanije
- Profil regrutera

**Test Objectives:**

The number of test cases executed: 45

The number of test cases pass: 40

The number of test cases fail: 5

Pass percentage: 88.89%

Fail percentage: 11.11%

Comment: Blocker issues are not found.  

**Defects:**

Total number of bugs: 5

There are 4 functional and 1 non-functional bugs (this one non-functional bug is a visual bug).

Breakdown by Severity and Priority: There are 2 bugs with Medium Priority and Medium Severity; 1 bug with Low Priority and Low Severity; 1 bug with High Priority and High Severity; 1 bug with Critical Priority and High Severity.

**Test Execution Details**

Number of Test by type:

- Passed: 40
- Failed: 5
- Skipped: 0


**Bug1**

**Summary:** Profile tab - Some sections are cut off at the end of the page.

**Actual result:** In the profile tab in the sections “Benefiti” and “Veštine i bedževi”** squares in the last row are cut off.

**Attachment:**


**Bug2**

**Summary:** Profile - Technologies - User can check more technologies than the limit allows.

**Actual result:** The user managed to check 21 technologies, and the counter shows number 20.

**Attachment:** 
<https://drive.google.com/file/d/1znrC7kUvc3lwFFezHwELRaSg_7qJwlIE/view?usp=drive_link> 

**Bug3**

**Summary:** Candidate profile and MatChat  -**  The data shown in percentages do not match.

**Actual result:** The candidate's profile (user Marija Takic) says: Technologies 100%, Benefits 100%. When the *MatChat* is opened, there is different data in the message: Technologies 50%, Benefits 28%.

**Attachment:**




**Bug4**

**Summary:** Job offer (Home page) does not match with the user's qualifications.

**Actual result:**  The data shown in percentages do not match. It is about the user "Marija Takić", and the job offer that does not match is "DevOps Engineer".

**Attachment:** 
<https://drive.google.com/file/d/1TNVc-AV_wvaU7OlSst9HbEBY9CJSJIXI/view?usp=drive_link> 


**Bug5**

**Summary:**  Profile - Technologies - The counter does not always show the correct number of checked technologies.

**Actual result:** Counter number decreases by one.

**Attachment:** 

<https://drive.google.com/file/d/1-O_75NPDstV33Kp-wzcqv0PVfIdELVX2/view?usp=drive_link> 


**Test Environment**

Devices:  

- Phone model: Xiaomi Redmi Note 9 pro (resolution 1080 x 2400); 
- Laptop Lenovo T470 (resolution 1920 x 1080), Windows 10 Pro, Google Chrome version 117.

Tools:

- Chrome DevTools

**Recommendations**

In the next sprint focus should be on “Profil” page. Since this is the page where I found the most bugs, we can add new features that will be useful to users and that can improve the overall experience of the app.

**Improvements**

**Mobile application**

**1.**

**Current:** If the user accidentally rejects the job and wants to go back to confirm it, the user cannot do it.

**Request:** Create a page where there will be a list of all active jobs that the user has rejected. If the user opens one of those jobs, there’s a possibility to swipe again if the user is interested.

**Reason:** The user can return to the desired job ad at any time.

**2.**

**Current:** In the “Profil” tab, in the section “Iskustvo”  where the user indicates the number of years of experience in the selected technologies, the maximum number that can be entered is 20.

**Request:** Allow the user to enter a bigger number, do not limit it to 20.

**Reason:** The user might have more than 20 years of experience.

**3.**

**Current:** In the “Profil” tab, in the section “Iskustvo” where the user indicates the number of years of experience in the selected technologies, if the user wants to put 15, he must manually click on the plus sign 15 times.

**Request:** Create a field where the user will simply be able to enter the desired number.

**Reason:** It's easier to use and doesn't take much time.

**4.**

**Current:** In the “Profil” tab, in the section “Tehnologije” where the user indicates which technologies he knows, the maximum number of technologies that can be entered is 20.

**Request:** Allow the user to enter a bigger number of technologies, do not limit it to 20.

**Reason:** The user might know more than 20 technologies.

**5.**

**Current:** In the “Profil” tab, in the section “Veštine i bedževi”, the user can choose up to 12 skills.

**Request:** Create a field called "other" where the user can enter his skill that is not offered. In that field, the user can list the skills, separating them with a comma. It would only apply to technical skills.

**Reason:** Maybe the user has more skills that are not offered.

**6.**

**Current:** On the home page there is no button to refresh the page.

**Request:** Create a button that will refresh the home page.

**Reason:** The user doesn’t have to log out of the application and log in again every time in order for the home page to be refreshed. The "refresh" button will make it much easier for the user.


**7.**

**Current:** On the “Prijava/Registracija” page, when the user clicks on the “NASTAVI DALJE” button without filling in the email field, no error message is displayed.

**Request:** Insert the error message “Email je obavezan” when the “NASTAVI DALJE” button is clicked without entering an email in the email field.

**Reason:** The user should clearly know what to do if accidentally clicks a button “NASTAVI DALJE”. It will be much easier for the user to register.

**Web application**

**1.**

**Current:** In the MatChat chat window size is not as expected. The font is really small.

**Request:** Increase the size of the chat window to full screen.

**Reason:** When the chat window is maximised it will be much easier to view and use.

**2.**

**Current:** On the homepage where there are job ads, the bold headings above are not readable. (ID, Ad Name, Status, Candidates, Matches, Archive, Edit, Duplicate).

**Request:** Change the size of all names, maybe change the colour to make them stand out from the rest of the text.

**Reason:** It will look much better and be easier to read and navigate.

**3.**

**Current:** On the homepage where there are job offers, there is no button at the end of the page that the user can use to return to the beginning.

**Request:** At the end of the page, place a button to return to the beginning.

**Reason:** When there are many job ads, this button will make it much easier for the user to navigate the page. Page scrolling takes a lot of time.


**Exit Criteria**

All critical issues are closed.

Any other open issues have an action planned and are targeted for the next release cycle.

